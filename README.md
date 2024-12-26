# Blinkit-like E-Commerce Platform  

![Alt text](Thumnails.png?raw=true "Project Thumbnail")

Build a complete e-commerce platform that looks like Blinkit using the **MERN** stack!  
In this project, I have created an online shopping site with key features, including:  
- **Product Uploads**  
- **Admin Panel**  
- **Category and Subcategory Management**  

We use **access and refresh tokens** for secure user authentication. The project also includes:  
- Password recovery  
- OTP-based email verification  
- Secure authentication processes  
---

## Demo  

![Alt text](Demo%201.gif?raw=true "Demo 1")  
![Alt text](Demo%202.gif?raw=true "Demo 2")  

---

## Technology Stack  

### Frontend  
- **React**  
- **Tailwind CSS**  
- **Redux**  

### Backend  
- **Express.js**  
- **MongoDB**  

### Additional Features  
- **Image Handling**: Multer, Cloudinary  
- **Payment Gateway**: Stripe  
- **Email Service**: Resend  

---

### .env.example Configuration

To run the server, configure the environment variables by creating a `.env` file based on the template below. Replace the placeholders with your actual values.

```bash
PORT=8080
MONGODB_URI=mongodb+srv://<username>:<password>@<cluster_url>?retryWrites=true&w=majority&appName=<cluster_name>
RESEND_API=<your_resend_api_key>
STRIPE_SECRET_KEY=<your_stripe_secret_key>
SECRET_KEY_ACCESS_TOKEN=<your_access_token_secret>
SECRET_KEY_REFRESH_TOKEN=<your_refresh_token_secret>
CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
FRONTEND_URL=http://localhost:5173

## Assets File  

**Google Drive Link**:  
[Download Assets](https://drive.google.com/drive/folders/1llzO3ts3NJKrQ0A2XWZYaO-T0Qnyq6yO?usp=sharing)  

---

## Schema Design  

**Schema PDF**:  
[View Schema Design](https://github.com/user-attachments/files/18254021/Schema.pdf)  
