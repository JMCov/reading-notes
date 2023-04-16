# React Native

## getting started with react native

**Name three Core Components of React Native and describe what they do.**

1. View: A View is like a container for other components. It is used to define the layout of the app's user interface. It can be thought of as similar to a div element in HTML.

2. Text: The Text component is used to display text on the screen. It supports basic styling and formatting, such as setting the font size and color.

3. StyleSheet: The StyleSheet component is used to define styles for the app's components. It is similar to CSS in web development and allows for consistent styling across the app.

**What problem does React Native solve (why call it native)?**

React Native is called "native" because it allows developers to create mobile apps that are native to a specific platform, such as iOS or Android. React Native accomplishes this by using native components rather than web components, which can result in a faster and smoother user experience.

**What are the building blocks of a React Native app? How does that compare to a React app?**

The building blocks of a React Native app include components, state, and props.

## expo

**What solution does expo provide?**

1. A command-line interface (CLI) that simplifies the process of creating, developing, and publishing React Native apps.

2. A set of APIs and libraries for accessing native device functionality such as the camera, contacts, and location services.

**Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.**

no build configuration

**What is the difference between React Native and Expo?**

One of the key differences between React Native and Expo is that Expo abstracts away much of the native code and provides a set of pre-built components and APIs that developers can use. React Native, on the other hand, requires developers to write more custom native code to achieve the same functionality. This makes Expo a great choice for building simple and straightforward apps, while React Native is better suited for more complex projects where fine-grained control is required.

## ejecting

**What does “eject” mean within the context of Expo?**

In the context of Expo, "eject" refers to the process of generating a native iOS or Android project from an existing Expo project. Ejecting allows developers to access the underlying native code and modify it directly, which provides more control and flexibility but also requires more configuration and maintenance.

**When should you not eject?**

Developers should not eject if they are not comfortable working with native code or if they do not require the advanced features or customization options provided by native code

**Why might you choose to eject?**

Developers might choose to eject if they require access to native functionality or if they need to modify the native code to achieve specific functionality that is not available through Expo

[Back to Home](../README.md)