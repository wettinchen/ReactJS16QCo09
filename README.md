## ReactJS Chapter 16
It is my coding practice with the TUTORIAL of Dave Gray. 

## Source
### Dave Gray 的 Reactjs 課程
https://youtube.com/playlist?list=PL0Zuz27SZ-6PrE9srvEn8nbhOOyxnWXfp
### Dave Gray 的 YouTube 頻道
https://www.youtube.com/@DaveGrayTeachesCode

## ReactJS Chapter 16
   Quick Concept outline
   中文摘要說明與重點提問
   
###  1. Intro 
        教學影片固定的開頭和摘要說明

###  2. Welcome <Code更動>
        

###  3. Project Preview
        專案預覽
        在 git bash 輸入 npx create-react-app <檔案名稱>

###  4. Quick Setup Guide <Code更動>
        在 git bash 輸入 npm i react-router-dom -S

###  5. Wrapping the App component in React Router <Code更動>
        在 index.js 中，
        從 "react-router-dom" 匯入 { BrowerRouter as Router, Routes, Route }
        新增 <Router></Router>，將 <Routes></Routes> 放入
        並將 App 修改為 <Route path="/*" element={<App />} />

###  6. Identifying all of the components <Code更動>
        在 App.js 匯入 Layout
        Home, NewPost, PostPage, About, Missing,
        { Route, Routes, useNavigate }
        { useState, useEffect }

        新增 Layout.js，
        在 Layout.js 匯入 Header, Nav, Footer

###  7. Creating the functional components <Code更動>
        新增 Header.js, Nav.js, Footer.js,
        Home.js, NewPost.js, PostPage.js, About.js, Missing.js,

###  8. Placing the components in JSX <Code更動>
        放置 <Header/>, <Nav/>, <Footer/>, 
        <Home/>, <NewPost/>, <PostPage/>, <About/>, <Missing/>

###  9. Adding routes for the components <Code更動>
        新增 <Routes></Routes>
        新增 <Route></Route>， element 為 <Layout .>
        新增 <Route />，
        element 為 <Home/>, <NewPost/>, <PostPage/>, <About/>, <Missing/>
        新增<Route></Route>，path 為 "post"
        將 <NewPost/>, <PostPage/> 放入
        在 git bash 輸入 npm start

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
