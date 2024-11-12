# Cartoonify App 🎨✨

Welcome to the **Cartoonify App**! Transform your photos into stunning, cartoon-style images in just a few clicks! Whether you want to add a fun twist to your selfies or create cartoon versions of your favorite pictures, this web-based application makes it quick, simple, and enjoyable. Built with Python, OpenCV, Streamlit, and SQLite, the app features secure user authentication, image history, and a smooth user interface.

## Features 🚀

### 🎨 **Cartoonify Your Image**
Transform any photo into a unique cartoon-style image using advanced image processing techniques like edge detection, bilateral filtering, and color quantization.

### 🔒 **User Authentication**
- Secure sign-up and login functionality.
- Passwords are securely hashed with `bcrypt`.
- Manage your profile and track your history.

### 🖼️ **Image History**
- Save and view previously cartoonified images.
- Easily access your gallery anytime.

### 🌟 **Interactive UI**
- Beautiful, responsive user interface powered by **Streamlit**.
- No setup required—just upload and go!

## Tech Stack 🛠️

This app is built with the following technologies:

- **Python**: The main programming language for backend processing.
- **OpenCV**: Used for image processing, including cartoonification and transformations.
- **Streamlit**: The UI framework for creating the app’s interface.
- **SQLite**: Lightweight database for managing user authentication and storing images.
- **bcrypt**: A library for securely hashing passwords.
- **Pillow**: Used for handling image uploads and manipulations.

## Installation Guide 🚀

To run **Cartoonify App** locally, follow these simple steps:

### 1. Clone the Repository

Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/yourusername/cartoonify-app.git
cd cartoonify-app
```

### 2. Install Dependencies

Install the necessary Python libraries using pip:

```bash
pip install -r requirements.txt
```

### 3. Run the Application

Start the app with this command:

```bash
streamlit run app.py
```

### 4. Access the App

Open your browser and go to `http://localhost:8501`. Start cartoonifying your images right away!

## Usage 📖

Once the app is up and running, here's how to use it:

### 1. **Sign Up or Log In**
- **Sign Up** if you're a new user by providing your email and creating a password.
- **Log In** with your credentials if you're an existing user.

### 2. **Upload Your Image**
- Click the **Upload Image** button and select an image from your device.

### 3. **Cartoonify the Image**
- After uploading, hit **Cartoonify**. Watch as your image is transformed into a vibrant cartoon-style version in real-time!

### 4. **Save & View Image History**
- Save your cartoonified images to your profile by clicking **Save Image**.
- View all previously cartoonified images in the **Image History** section.

### 5. **Log Out**
- When you're done, click on **Log Out** to securely exit your account.

## How Cartoonification Works 🎨

The app applies advanced image processing techniques to transform your photos into cartoons:

### 1. **Edge Detection** 
The app uses **Canny edge detection** to detect edges in the image, giving it a hand-drawn look.

### 2. **Bilateral Filtering** 
We apply **bilateral filtering** to smooth the colors while preserving the sharp edges, creating a clean cartoonish effect.

### 3. **Color Quantization**
The app reduces the number of colors in the image using **color quantization** to make the image look more like a painting or cartoon.

## Demo 🎥

Check out the live demo here: [Cartoonify App Demo](https://www.linkedin.com/posts/abdullah-mir-211658230_imageprocessing-python-computervision-activity-7258410270388092928-TMSu?utm_source=share&utm_medium=member_desktop)

## Contributing 💡

We welcome contributions to improve **Cartoonify App**! Here’s how you can contribute:

1. **Fork** the repository.
2. **Create a new branch** for your feature or fix.
3. **Commit** your changes and push them.
4. **Submit a pull request** explaining your changes.

## License 📜

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Enjoy cartoonifying your images, and have fun with the **Cartoonify App**! 😎🎉
