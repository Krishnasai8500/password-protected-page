# Password Protected Page
Welcome to the **Password Protected Page** project! This Express.js web application implements a simple authentication system where users must enter a correct password to access a secret page. When users enter the password, they are either granted access to the protected content or remain on the homepage depending on the validation result.

## 🚀 Features
- **Password Validation**: Validates user-entered passwords against a stored value
- **Protected Route**: Secure access to a secret page
- **Redirect System**:
  - Successful login redirects to secret page
  - Failed attempts keep users on homepage
- **Simple UI**: Clean interface for password entry

## 🖥 Technologies Used
This project utilizes the following technologies:
- **Node.js**: JavaScript runtime environment
- **Express.js**: Web application framework
- **Body-Parser**: Middleware for parsing HTTP request bodies
- **HTML/CSS**: Frontend interface

## 📦 Prerequisites
Make sure you have the following installed before running the project:
- **Node.js** (LTS version is recommended): [Download Node.js](https://nodejs.org/)
- **npm**: The Node.js package manager (comes with Node.js installation)

## 🏁 Installation
Follow these steps to get the project up and running:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/password-protected-page.git
   cd password-protected-page
   ```

2. **Install the dependencies**:
   ```bash
   npm install
   ```

## 🎬 Usage
1. **Start the server**:
   ```bash
   node solution.js
   ```

2. **Access the application**:
   - Open your browser and navigate to `http://localhost:3000`
   - Enter the password when prompted
   - Access granted password: `ILoveProgramming`

## 📂 Project Structure
```
/project-root
├── /public
│   ├── index.html    # Homepage with password input
│   └── secret.html   # Protected content page
└── solution.js       # Main server file
```

## 💡 Example
Here's how the application flow works:
1. Visit the homepage
2. Enter password "ILoveProgramming"
3. If correct: Redirected to secret page
4. If incorrect: Remain on homepage

## 🔧 Dependencies
This project uses the following dependencies:
- **express**: Web framework for Node.js
- **body-parser**: Parse incoming request bodies
- **path**: Built-in Node.js module for file paths

## 🌐 Deployment
You can deploy this application on various platforms:
- **Render**: Cloud platform with easy deployment
- **Vercel**: Serverless platform for Node.js applications

## 📄 License
This project is licensed under the MIT License. See the LICENSE file for more details.

## 🤝 Contributing
Feel free to fork the project and submit pull requests for any improvements!

## ✅ You're all set! Happy Coding!
