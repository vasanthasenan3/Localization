# 🌍 WPF Localization

A C# WPF application that demonstrates employee registration and multilingual localization using resource files. This project also covers JSON serialization and file handling.

## ✨ Features

* 📝 Employee registration form
* 🌐 Multilingual resource files for English, Hindi, and Tamil
* 🏷️ Localized UI text using the `x:Static` markup extension
* ⚙️ Culture configuration using `CultureInfo`
* 📦 JSON serialization using Newtonsoft.Json
* 💾 Save employee details to text files
* 🔍 Check for existing usernames before saving
* ✅ Display registration success messages
* ⚠️ Show a message when a username already exists

## 🌐 Languages Supported

| Language     | Culture Code |
| ------------ | ------------ |
| 🇺🇸 English | `en-US`      |
| 🇮🇳 Hindi   | `hi-IN`      |
| 🇮🇳 Tamil   | `ta-IN`      |

## 🛠️ Technologies Used

* 💻 C#
* 🪟 Windows Presentation Foundation (WPF)
* 🎨 XAML
* ⚙️ .NET
* 📄 Resource Files (`.resx`)
* 📦 Newtonsoft.Json
* 🗂️ System.IO

## 📚 Concepts Covered

* 🌍 Localization in WPF
* 📄 Resource Files and Resource Properties
* 🏷️ `x:Static` Markup Extension
* ⚙️ `CultureInfo` and UI Culture
* 📝 Employee Registration
* 📦 JSON Serialization
* 📁 `Directory.CreateDirectory()`
* 🗂️ `Path.Combine()`
* 🔍 `File.Exists()`
* 💾 `File.WriteAllText()`
* 🖱️ Button Click Events
* 🔤 Basic Input Handling

## 🔄 How It Works

1. 📝 Enter employee details in the registration form.
2. 🌐 The UI retrieves localized text from resource files.
3. 🖱️ Click the **Generate** button.
4. 📦 The application stores the entered details in a C# object.
5. 🔄 Newtonsoft.Json converts the employee data into JSON format.
6. 🔍 The application checks whether a file already exists for the entered username.
7. ⚠️ If the file exists, a message asks the user to choose a different username.
8. 💾 Otherwise, the registration details are saved to a text file.

## 📂 Data Storage

Registration files are stored in the `BillApp` folder inside the user's Pictures directory.

Each registration file is named using the entered username.

## 🎯 Project Purpose

The purpose of this project is to gain practical experience with WPF localization, resource files, culture configuration, JSON serialization, and file handling in C#.

It also helps build an understanding of how multilingual resources can be organized in desktop applications.

## 🔐 Security Note

This project is intended for learning purposes. The current implementation stores password values in plain text within files. Real-world applications should never store passwords this way; they should use an appropriate secure password-hashing approach.
