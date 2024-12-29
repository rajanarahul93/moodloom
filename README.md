# MoodLoom – Full Stack Mood Tracking App

**MoodLoom** is a modern and dynamic mood-tracking web application built with **Next.js 14**, **Firebase**, and **TailwindCSS**. It allows users to log, track, and visualize their emotions over time. With real-time updates, a sleek UI, and seamless user authentication, this app provides valuable insights into emotional trends and well-being.

This project demonstrates full-stack web development, from front-end design to back-end integration with Firebase services.

## Features

- **User Authentication**: Users can sign up, log in, and manage their account securely via Firebase Authentication.
- **Mood Tracking**: Track and log daily moods with personalized input.
- **Data Visualization**: Visualize mood trends over time with beautiful, responsive charts.
- **Responsive Design**: Built using TailwindCSS to ensure the app looks great on any device.
- **Real-Time Updates**: Utilizes Firebase Firestore to store and sync user data in real time.

## Technologies Used

- **Next.js 14**: A powerful React framework for building fast, scalable, and SEO-friendly applications.
- **Firebase**: Used for authentication, database management (Firestore), and real-time data syncing.
- **TailwindCSS**: A utility-first CSS framework for creating responsive, customizable, and modern UI designs.
- **Chart.js**: For visualizing mood trends over time in beautiful, interactive charts.

## Installation

### 1. Clone the repository:

```bash
git clone https://github.com/rajanarahul93/moodloom.git
cd moodloom
```

### 2. Install dependencies:

```bash
npm install
```

### 3. Set up Firebase:

- Go to [Firebase Console](https://console.firebase.google.com/).
- Create a new project and configure Firebase Authentication and Firestore.
- Create a `.env.local` file in the root of your project and add the Firebase config variables (you can find them in the Firebase Console).

```plaintext
NEXT_PUBLIC_API_KEY=your-api-key
NEXT_PUBLIC_AUTH_DOMAIN=your-auth-domain
NEXT_PUBLIC_PROJECT_ID=your-project-id
NEXT_PUBLIC_STORAGE_BUCKET=your-storage-bucket
NEXT_PUBLIC_MESSAGING_SENDER_ID=your-sender-id
NEXT_PUBLIC_APP_ID=your-app-id
```

### 4. Run the app locally:

```bash
npm run dev
```

Your app should now be running at `http://localhost:3000`.

## Deployment

To deploy your project, you can use Firebase Hosting:

1. **Install Firebase CLI**:

```bash
npm install -g firebase-tools
```

2. **Login to Firebase**:

```bash
firebase login
```

3. **Initialize Firebase**:

```bash
firebase init
```

4. **Deploy the app**:

```bash
firebase deploy
```

## How it Works

1. **User Authentication**: Firebase Authentication manages user registration, login, and password recovery. The app allows users to sign up, log in, and securely store user data.
2. **Mood Logging**: After logging in, users can log their daily mood using predefined options or custom inputs.
3. **Data Visualization**: The app tracks mood data and displays a graphical representation of mood trends using **Chart.js**.
4. **Real-Time Syncing**: All mood logs are stored in Firebase Firestore, allowing for real-time data syncing across devices.

## Contributing

Feel free to fork the repository, make improvements, or submit pull requests for features you’d like to add! Any contributions are welcome.
