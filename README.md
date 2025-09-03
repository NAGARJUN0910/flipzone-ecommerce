# 🛒 FlipZone – E-Commerce Web Application

FlipZone is a **full-stack e-commerce application** built using **Spring Boot, MySQL, Thymeleaf, and JavaScript**.  
It provides a seamless shopping experience with product management, cart system, payment gateway integration, and user authentication.  

---

## 🚀 Features

- 👤 **User Authentication & Authorization**
  - Signup, login, logout (session-based authentication)
  - Role-based access for Admin & Customers  

- 📦 **Product Management**
  - Admin can **add, edit, delete, and view products**
  - Manage stock, prices, and product images (Cloudinary integration)

- 🛍 **Shopping Cart & Checkout**
  - Add/remove products to cart
  - View cart items dynamically
  - Checkout with real-time price calculation

- 💳 **Payment Integration**
  - Razorpay payment gateway
  - Secure payment handling
  - Transaction callback support  

- 📧 **Email Notifications**
  - Order confirmation emails using **Spring Mail**  

- 📱 **Responsive UI**
  - Bootstrap 5 + Custom CSS
  - Smooth animations for better user experience  

---

## 🛠 Tech Stack

**Backend:** Spring Boot, Spring Data JPA, Hibernate  
**Frontend:** Thymeleaf, HTML5, CSS3, Bootstrap 5, JavaScript  
**Database:** MySQL  
**Cloud Storage:** Cloudinary (for product images)  
**Payment Gateway:** Razorpay  
**Mail Service:** Gmail SMTP  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/your-username/flipzone.git
cd flipzone

2️⃣ Configure Database
Create a MySQL database named flipzone (or update in application.properties):
spring.datasource.url=jdbc:mysql://localhost:3306/flipzone?createDatabaseIfNotExist=true
spring.datasource.username=your_Username
spring.datasource.password=your_Password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

3️⃣ Configure Mail & Cloudinary
Update application.properties with your credentials:
spring.mail.username=your-email@gmail.com
spring.mail.password=your-app-password

CLOUDINARY_URL=cloudinary://API_KEY:API_SECRET@CLOUD_NAME
razor-pay.api.key=your_razorpay_key
razor-pay.api.secret=your_razorpay_secret

4️⃣ Run the Application
mvn spring-boot:run
Access the app at 👉 http://localhost:2002/

👨‍💻 Usage
Admin Panel
URL: /admin/home
Default Credentials:
     Email: admin@jsp.com
  Password: admin
Customer:
        - Signup from /signup
        - Login from /login
        - Browse, add to cart, and checkout
        
📌 Future Enhancements

✅ Add product search & filters

✅ Implement wishlist feature

✅ Add order tracking system

✅ REST API endpoints for mobile app integration

🤝 Contributing

**Fork the repository**
1.Create your feature branch (git checkout -b feature-xyz)
2.Commit your changes (git commit -m 'Add xyz feature')
3.Push to the branch (git push origin feature-xyz)
4.Open a Pull Request

👤 Author
NAGARJUN B N
💼 Java Full Stack Developer | ☁️ Cloud Enthusiast | 💡 Problem Solver
🔗 [Portfolio](https://nagarjun0910.github.io/portfolio0910/)
 | [LinkedIn](https://www.linkedin.com/in/nagarjun-b-n-909b69290/)
 | [GitHub](https://github.com/NAGARJUN0910/NAGARJUN0910)
