<h1>watch cart</h1>

<h3>Introduction</h3>
<p>watchcart is an e-commerce website for selling branded watches. This website includes a list of modules. There is an admin Section and User Section. Admin can login using predefined user id and password. Admin can control users and products. Users can browse and buy products. There is a payment gateway for payment methods.

</p>
<h1>Run</h1>
<p>To run this application, you have to set your own environmental variables. For security reasons, some variables have been hidden from view and used as environmental variables with the help of dotenv package. Below are the variables that you need to set in order to run the application:</p>
<li>key_id: This is the razorpay key_Id (string).</li>
<li>key_secret: This is the razorpay key_Secret (string).</li>
<li>email:This is the email id used for nodemailer(string)</li>
<li>password : This is the password used for nodemailer(String)</li>
<p>After you've set these environmental variables in the .env file at the root of the project, and intsall node modules using npm install</p>
<p>Now you can run npm start in the terminal and the application should work.

</p>
<h1>Technology<h1/>
  <ul>
  <li>Node.js</li>

   <li>Express</li>
   <li>MongoDb</li>
   <li>Bootstrap</li>
   <li>Razorpay</li>
   <li>Nodemailer</li>
  <li>ajax</li>
  </ul>
  <p>Deployed in AWS EC2 instance with Nginx reverse proxy</p>
  <h1>Features</h1>
  <p>The application displays a watach store that contains different branded watches  and their information.</p>
  <h6>Users can do the following:</h6>
  <li>Login and signup with OTP verification using nodemailer.</li>
  <li>Through otp verification, the user can manage forgotten passwords.</li>
  <li>Users can change their password and set a new one.</li>
  <li>Users can change their address and personal info.</li>
  <li>Products can be viewed from landing page with categories </li>
  <li>User can Add product to cart and wishlist.</li>
  <li>User can view single product details.</li>
  <li>Cart with subtotal and grand Total.</li>
  <li>Can Add multiple address including shipping address.</li>
  <li>Category wise render of all products.</li>
  <li>Payment Gateway is integrated with RAZOR PAY.</li>
  <li>The user can cancel the purchased products and the payment is refundable</li>
  <li>User can see the purchase/order history.</li>
  <h6>Admins can do the following:</h6>
  <li>Admin login with pre defined credentials.</li>
   <li>Admin Dashboard is implemented with sales reports.</li>
   <li>Admin can handle user block , unblock and delete.</li>
   <li>Add banners</li>
   <li>Can add product and change product details.</li>
  <li>Can add category and sub categories.
</li>
  

  <li>Admin can change the user order status (Confirmed, Delivered).</li>
  <li>Admin can cancel user orders if it’s pending (status)</li>
  <h2>Author</h2>
  <h6>Sreekanth ps</h6>
