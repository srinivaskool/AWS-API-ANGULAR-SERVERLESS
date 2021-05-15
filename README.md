# Compare Yourself

In this Serverless portal, you can signup and compare yourself with the other members of the website. The comparison can be in ascending or descending order. 
<br>
<p align="center">
  <img  src="README_IMAGES\Structure.PNG" >  
</p>

### Table of Contents

- [Description](#description)
- [Process](#analysis)
- [Working Image](#results)
- [Project Layout](#project-layout)
- [References](#references)
- [Author Info](#author-info)

---

## Description

<br>

In this Serverless portal, you can signup and compare yourself with the other members of the website. The comparison can be in ascending or descending order. After you signup, we authenticate and store your details like age, income in Dynamo DB, and the complete backend service ios given by our API. We can use POST, GET, DELETE requests on the API. As we have to send particular information so there are two types of getting one is for all data retrieval and the other we pass id by param so the DynamoDB will be searched and we get only details of that ID data. For all the requests the CORS is enabled as we send a request through different domain then API is deployed. 

### Services Used

- AWS API Gateway
- AWS DyanamoDB
- AWS Lambda
- AWS Cognito

### For Execution
You need an AWS account. Then clone the repository and create Lambda and S3 buckets with the same names given in the code. Then run npm install and then run the app using `npm start` or `ng serve` for a dev server. Navigate to `http://localhost:4200/`. the app will automatically reload if you change any of the source files.


---

## Process
<br >
<p align="center">
  <img  src="README_IMAGES\Process.png" >  
</p>

---

## Working Image
<br >
<p align="center">
  <img  src="README_IMAGES\Working.PNG" >  
</p>

#### [Back To The Top](#Compare Yourself)

---

## Project Layout

```
AWS-API-ANGULAR-SERVERLESS
├─ e2e
│  ├─ app.e2e-spec.ts
│  └─ app.po.ts
├─ karma.conf.js
├─ package-lock.json
├─ package.json
├─ protractor.conf.js
├─ README.md
├─ README_IMAGES
│  ├─ 2.PNG
│  ├─ 3.PNG
│  ├─ 4.PNG
│  ├─ 5.PNG
│  ├─ 7.PNG
│  └─ Capture.PNG
├─ src
│  ├─ app
│  │  ├─ app-routing.module.ts
│  │  ├─ app.component.css
│  │  ├─ app.component.html
│  │  ├─ app.component.ts
│  │  ├─ app.module.ts
│  │  ├─ compare
│  │  │  ├─ compare-data.model.ts
│  │  │  ├─ compare-input
│  │  │  │  ├─ compare-input.component.css
│  │  │  │  ├─ compare-input.component.html
│  │  │  │  └─ compare-input.component.ts
│  │  │  ├─ compare-results
│  │  │  │  ├─ compare-results.component.css
│  │  │  │  ├─ compare-results.component.html
│  │  │  │  └─ compare-results.component.ts
│  │  │  ├─ compare.component.css
│  │  │  ├─ compare.component.html
│  │  │  ├─ compare.component.ts
│  │  │  └─ compare.service.ts
│  │  └─ user
│  │     ├─ auth-guard.service.ts
│  │     ├─ auth.service.ts
│  │     ├─ signin
│  │     │  ├─ signin.component.css
│  │     │  ├─ signin.component.html
│  │     │  └─ signin.component.ts
│  │     ├─ signup
│  │     │  ├─ signup.component.css
│  │     │  ├─ signup.component.html
│  │     │  └─ signup.component.ts
│  │     └─ user.model.ts
│  ├─ favicon.ico
│  ├─ index.html
│  ├─ main.ts
│  ├─ polyfills.ts
│  ├─ styles.css
│  ├─ test.ts
│  ├─ tsconfig.app.json
│  └─ tsconfig.spec.json
├─ tsconfig.json
└─ tslint.json

```

---

## References

- [AWS](https://aws.amazon.com/)
- [Angular CLI](https://github.com/angular/angular-cli)
---

## Author Info

- LinkedIn - [Srinivas K](https://www.linkedin.com/in/srinivas-konduri/)
- Github - [Srinivas K](https://github.com/srinivaskool)

#### [Back To The Top](#Compare Yourself)



