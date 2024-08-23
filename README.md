# Social Media App with Expo Go and Supabase

Yuber is a ride-booking application that provides a seamless and secure user experience. The app features full user authentication and sign-in with Google, powered by Clerk, ensuring a streamlined registration and login process. User data is securely stored on Neon, a serverless Postgres platform. Yuber's main screens include a ride history view, a user profile section, and a booking interface. To book a ride, users select their start location—defaulting to their current location—and choose a destination. Yuber then suggests nearby drivers, providing detailed information such as pricing, distance, fees, and available car seats. Payment for rides is conveniently handled through Stripe, allowing users to enter their payment details and confirm their ride with ease. Once payment is complete, users are ready to embark on their journey.

Tools Used: React Native, Expo Go, Clerk, Neon, Stripe, Geoapify, TailWindCSS

## Demo Images

### Onboarding Screens

<img src="assets/screenshots/onboarding1.PNG" width="200" /> <img src="assets/screenshots/onboarding2.PNG" width="200" /> <img src="assets/screenshots/onboarding3.PNG" width="200" />

### Sign up / Sign in Screens / Google Login

<img src="assets/screenshots/signup.PNG" width="200" /> <img src="assets/screenshots/signin.PNG" width="200" /> <img src="assets/screenshots/googlelogin.PNG" width="200" />

### Main Tab Layout

<img src="assets/screenshots/home.PNG" width="200" /> <img src="assets/screenshots/rides.PNG" width="200" /> <img src="assets/screenshots/chat.PNG" width="200" /> <img src="assets/screenshots/profile.PNG" width="200" />

### Choose Ride Screen

<img src="assets/screenshots/choose_ride1.PNG" width="200" /> <img src="assets/screenshots/choose_ride2.PNG" width="200" />

### Choose Driver Screen

<img src="assets/screenshots/choose_driver1.PNG" width="200" /> <img src="assets/screenshots/choose_driver2.PNG" width="200" />

### Confirm Screen

<img src="assets/screenshots/confirm.PNG" width="200" />

### Stripe Pay Modal Screen

<img src="assets/screenshots/pay1.PNG" width="200" /> <img src="assets/screenshots/pay2.PNG" width="200" /> <img src="assets/screenshots/pay3.PNG" width="200" />

### Complete Screen

<img src="assets/screenshots/complete.PNG" width="200" />

# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
