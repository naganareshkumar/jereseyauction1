# README

About Gundain
    Main theme of the project is sell autographed jersey's or sports player game items, which are been used in playing. The items will be sold based on auction who wins the bidding of particular item( like, jersey's, baseball bat, basket ball .. etc). In addition to auction we are working on selling game kit like player names on jersey's, baseball kit, basketball kit in the store feature, also we implementing a feature to buy tickets online for a particular match and users can view upcoming games schedule that user can't miss his/her favourite player match.

Project Execution:
step1: clone main branch from gundian project
step2: run the command bundle install 
( to make sure the devise gem and active storage has successfully installed)
step3: run command yarn install 
step4:run command rails db:migrate:reset db:seed
step5: rails s

M1 features
1. For the milestone m1, we have demoed the bidding feature and buying tickets feature as we working in progress make sure work properly.
2. This features are implemeted without authentication and authoriaztion because active storage for storing images took long time to work feature properly.

Special instructions
1. For the feature bidding, user(bob) need to select seller option first, and then click on seller again on seller page it will redirect to create new page to sell his product.
2. After uploading the product image, the image option display choose file again on the feature ( dont be worry because you have uplaoded successfully but the UI changes are need, will implemented feature iteration), where you view the uploaded file name on mouse over on option.
3. After successful creation of item, seller(bob) can have option to sell directly from store or can proceed with auction.
4. Bidding page is in progress, upcoming feature it will be implemented sucessfully.



M2 features
1. For the milestone m2,we have accomplished the bidding feature and buying tickets feature.
2. We have completed all of the features for the m2 milestone. We have specifically upgraded functions such as auctioning, purchasing tickets, and bidding on merchandise.
3. Created model classes for buy now, payment, checkout, and shop in milestone M2.
4. Used the database to retrieve store items.
5. Determined the total cost of the tickets to be purchased.
6. We have completed the Game schedule Feature.
7. All of the project's functionalities have been implemented accordingly as mentioned.

Special Instructions
1. To know what is auction Gundain user can view the details in About page.
2. Another item to consider is that users may check complete match data through the Gameschedule, and from there, they can proceed to the tickets website if necessary.
3. To utilize the ticket function, store feature, or engage in a bid, the user must be logged in.
4. When the user specifies the total number of tickets, the total amount is calculated, and the user is brought to the payment page.
5. If a user bids on an auction item via the bidding function, the bid amount must be at least $10 more than the current bid amount.
6. If one user bids on a particular auction item, the bidding amount for all other users is updated.


Thank you,
TEAM GUNDAIN
