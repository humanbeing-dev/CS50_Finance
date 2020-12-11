# CS-50 Finance
Simple exercise of selling and buying stocks

## Table of Contents

## Function TODO
### register function
-[x] username - name="username" <br>
-[x] password - name="password" <br>
-[x] confirmation - name="confirmation" <br>

-[x] submit (POST to /register)
-[x] insert user to users (store hash of the users password) -> use generate_password_hash

### quote function
-[x] user input with stock's symbol (name="symbol")
-[x] submit user's input via POST to /quote
-[x] quote.html -> 
-[x] quoted.html

### buy function
-[x] user input with stock's symbol (name="symbol")
-[ ] apology if symbol does not exist
-[ ] user input with number of shares (name="shares")
-[ ] apology if input is not positive integer
-[ ] sumbit input via POST to /buy
-[ ] check current price of the stock
-[ ] check how much money does user have
-[ ] create new table purchases (purchase_id, user_id, price, time)
-[ ] create new table sales (sale_id, user_id, price, time)
-[ ] apology without purchase or sale when user cannot afford
-[ ] 