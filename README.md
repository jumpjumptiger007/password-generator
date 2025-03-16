# Strong Password Generator

A simple, secure, and user-friendly online password generator that helps users create high-strength random passwords.

🔗 **[Live Demo](https://yliu.tech/password-generator/)**

![Password Generator Preview](https://via.placeholder.com/800x400?text=Password+Generator+Preview)

## ✨ Features

- 🔐 Generate high-strength random passwords
- 📏 Customize password length (4-100 characters)
- 🔡 Select character types to include (uppercase letters, lowercase letters, numbers, special symbols)
- 👁️ Option to exclude visually similar characters (i, l, 1, o, 0, etc.)
- 🚫 Option to exclude hard-to-type special characters
- 📊 Visual password strength indicator
- 📋 One-click password copying
- 💾 Automatically saves the 10 most recently generated passwords
- 🌐 Runs entirely in the browser with no data sent to servers

## 🛠️ Technical Implementation

- Built with pure HTML, CSS, and JavaScript
- Responsive design that adapts to various screen sizes
- No backend required, runs completely client-side
- Uses LocalStorage to save password history
- Password strength analysis based on length, character diversity, and entropy calculation

## 🔍 Password Strength Criteria

Password strength is evaluated based on the following levels:

- **Very Weak**: Easily cracked in a short time
- **Weak**: Can potentially be cracked quickly
- **Moderate**: Takes a reasonable amount of time to crack
- **Strong**: Difficult to crack using conventional methods
- **Very Strong**: Virtually impossible to crack through brute force

## 🚀 How to Use

1. Visit the [Password Generator](https://yliu.tech/password-generator/)
2. Set your desired password length
3. Select the character types to include
4. Choose additional options if needed (exclude similar characters, etc.)
5. Click the "Generate Password" button
6. Click the "Copy" button to copy the generated password to your clipboard
7. Previously generated passwords will be displayed in the list below

## 💻 Local Deployment

To run this project locally:

1. Clone this repository
```bash
git clone https://github.com/jumpjumptiger007/password-generator.git
```

2. Open the `index.html` file in your browser

No other dependencies or package installations are required.

## 📝 Privacy Statement

- All operations are performed locally in your browser
- No user data is collected or transmitted
- Password history is only stored in LocalStorage on the user's device
- Generated passwords are not saved after closing the browser (unless manually saved)

## 📜 License

MIT License

## 🔮 Future Plans

- [ ] Add password export functionality
- [ ] Implement custom character set options
- [ ] Provide password memorization tips
- [ ] Add more language support
- [ ] Optimize password generation and strength estimation algorithms

## 🙏 Contributions and Feedback

Feedback and contributions via Issues or Pull Requests are welcome.
