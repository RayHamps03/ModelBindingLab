# Styling With Bootstrap
This repo uses Bootstrap, a web-development framework used to assist creation in fast and responsive websites. 

## Installation
There are multiple ways to install Bootstrap, and it is best to [refer to the installation documents](https://getbootstrap.com/docs/5.3/getting-started/download/) for more information.
This repo uses the ASP.NET Core Web App (Model-View-Controller) template in Visual Studio, which currently comes with Bootstrap 5 and is installed with the method below.
- [Install the latest version of Visual Studio](https://visualstudio.microsoft.com/)
- Install the ASP.NET and web development workload
  
  <img width="1231" height="621" alt="image" src="https://github.com/user-attachments/assets/66939af7-24f0-4acc-a2b9-f37d70c0983b" />
  
- After installation, create a new project using the ASP.NET Core Web App (Model-View-Controller) template
  
  <img width="877" height="569" alt="image" src="https://github.com/user-attachments/assets/eaacf7ed-729d-4e7a-8a70-922110109309" />

## Features 
Bootstrap contains many tools that assist in layout, styling, and general customization. You can [refer to the Bootstrap docs](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
for a complete list of features. Below are examples of styling with Bootstrap used in this repository.

### **Cards**
The User Profile page uses cards to separate information from each other in their own data containers that not only help organize the webpage layout, but code as well.  
Bootstrap docs provided code:
```
<div class="card">
  <div class="card-body">
    This is some text within a card body.
  </div>
</div>
```

### **Flex**
The User Profile page utilizes flex behavior to manage the layout of the cards, making it so that the GitHub URL and Skilled Languages cards are responsive to accomodate small screens.  
Bootstrap docs provided code:
```
<div class="d-flex p-2">I'm a flexbox container!</div>
```
