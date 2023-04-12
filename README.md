# Assignment 3

* *Date Created*: April 04 2023
* *Last Modification Date*: April 04 2023
* *Git URL*: https://git.cs.dal.ca/ppc/group_5_csci5709

## Authors

* [Abhinav Singh](abhinav.singh@dal.ca) 
* [Jaivik Tailor (B00915987)](jv711224@dal.ca)
* [Parth Champaneria](pr514457@dal.ca) 
* [Shivangkumar Gandhi](sh966188@dal.ca) 
* [Utsav Singh](ut796069@dal.ca)

## Login credentials

### Pet Owner login credentials
 - Username:sarahjayson28@hotmail.com
 - Password:password

## Vet login credentials
 - Username:pc@gmail.com
 - Password:12344321

## Admin login credentials
 - Username:admin@gmail.com
 - Password:123456789

 NOTE : The admin module is accessible at the URL : https://spontaneous-blancmange-9e6574.netlify.app/adminlogin

## Feature Developed

### Abhinav 
* Analytics module [Feature 1]
* Insurance purchase module [Feature 2]


### Jaivik 
* User Management [Feature 3]

### Parth
* Vet Appointment Booking Management for Pet Owner [Feature 4]
* Vet Catalogue Management [Feature 5]

### Shivang 
* Pet Medical Records Management for Vets and Pet Owners [Feature 6]

### Utsav 
* Appointment Management for Veterinarian [Feature 7]


## Tasks 
[Abhinav]
* View all insurances
* Payment page
* Analytics landing page
* view disease data in pie chart 
* View all the registered user per year per month

[Jaivik]
* Login for all users
* Registration for all users
* Forgot password via otp in a mail
* Logout

[Parth]
* View avaiable Vets
* Book an appointment with the Vet
* Modify an existing booking
* Cancel an existing booking
* View upcoming appointments for pet owner

[Shivang]
* Add medical record for a pet
* Update medical record for a pet 
* View medical records of a pet for vet
* View medical records of a pet for pet owner

[Utsav]
* View Upcoming Appointment
* Cancel Upcoming Appointment
* Add Availability

## Created files for Frontend 

Frontend Files

[Abhinav]
* client\src\pages\analytics\Analytics.js
* client\src\pages\analytics\Card.js
* client\src\pages\analytics\Chart.js
* client\src\pages\analytics\ChartBar.js
* client\src\pages\analytics\PieChart.js
* client\src\pages\analytics\RegistrationChart.js
* client\src\pages\analytics\RegistrationDate.js
* client\src\pages\analytics\RegistrationFilter.js
* client\src\pages\analytics\RegistrationItem.js
* client\src\pages\analytics\RegistrationList.js
* client\src\pages\analytics\RegistrationStats.js
* client\src\pages\insurance\Payment.js
* client\src\pages\insurance\ViewInsurances.js
* client\src\pages\analytics\Card.css
* client\src\pages\analytics\Chart.css
* client\src\pages\analytics\ChartBar.css
* client\src\pages\analytics\PieChart.css
* client\src\pages\analytics\RegistrationDate.css
* client\src\pages\analytics\RegistrationFilter.css
* client\src\pages\analytics\RegistrationList.css
* client\src\pages\analytics\RegistrationStats.css

[Jaivik]
* ForgotPassword.js(client\src\pages\ForgotPassword.js)
* Login.js(client\src\pages\Login.js)
* Otp.js(client\src\pages\Otp.js)
* Registration.js(client\src\pages\Registration.js)
* RegistrationDoctor.js(client\src\pages\RegistrationDoctor.js)
* AdminLogin.js(client\src\pages\AdminLogin.js)

[Parth]
* client/src/components/pet_owner/Star.js
* client/src/components/pet_owner/SuccessAlert.js
* client/src/components/pet_owner/TimeSlot.js
* client/src/components/pet_owner/TimeSlotBox.js
* client/src/pages/pet_owner/Appointment.js
* client/src/pages/pet_owner/DisplayVetList.js
* client/src/pages/pet_owner/ViewMedicalDetailsOwnerHome.js
* client/src/pages/pet_owner/ClinicAndVetDetails.js
* client/src/pages/pet_owner/OwnerPetMedicalDetails.js

[Shivang]
* client/src/pages/pet_owner/ViewMedicalDetailsOwnerHome.js
* client/src/pages/pet_owner/OwnerPetMedicalDetails.js
* client/src/pages/vet/ViewMedicalDetailsVetHome.js
* client/src/pages/vet/AddMedicalRecord.js
* client/src/pages/vet/UpdateMedicalRecord.js
* client/src/pages/vet/PetMedicalDetails.js
* client/src/components/common/AdminNavbar.js
* client/src/components/common/AdminSidebar.js
* client/src/components/common/HomeNavbar.js
* client/src/components/common/Navbar.js
* client/src/components/common/PetOwnerNavbar.js
* client/src/components/common/PetOwnerSidebar.js
* client/src/components/common/VetNavbar.js
* client/src/components/common/VetSidebar.js
* client/src/components/dashboard/PetOwnerDashboard.js
* client/src/components/dashboard/vetDashboard.js
* client/src/pages/HomePage.js

[Utsav]
* client/src/pages/vet/AddAvailability.js
* client/src/pages/vet/AppointmentCard.js
* client/src/pages/vet/AppointmentDetails.js
* client/src/pages/vet/AppointmentPage.js
* client/src/pages/vet/AddAvailability.js
* client/src/pages/vet/Calendar.js

## Created files for Backend 

[Abhinav]
* server\src\controllers\insuranceController.js
* server\src\models\insurancesModel.js

[Jaivik]
* pet_ownerModel.js (server\src\models\pet_ownerModel.js)
* vetsModel.js (server\src\models\vetsModel.js)
* adminModel.js (server\src\models\adminModel.js)
* user_registrationController.js (server\src\controllers\user_registrationController.js)

[Parth]
* server/src/routes/index.js
* server/src/database/database.js
* server/src/controllers/vetAvailabilityController.js
* server/src/controllers/vetsController.js
* server/src/controllers/appointmentsController.js
* server/src/models/appointmentsModel.js
* server/src/models/vetAvailabilityModel.js
* server/src/models/vetsModel.js

[Shivang]
* server/src/routes/index.js
* server/src/controllers/petsController.js
* server/src/models/petsModel.js

[Utsav]
* server/src/routes/index.js
* server/src/controllers/vetAvailabilityController.js
* server/src/controllers/appointmentsController.js
* server/src/models/appointmentsModel.js
* server/src/models/vetAvailabilityModel.js



### Prerequisites

To have a local copy of the Frontend part of the assignment up and running on your local machine, you will first need to install the dependencies by running the following commands

```
Download all the packages and their dependencies - npm install
Run the web application - npm start

```

To have a local copy of the Backend part of the assignment up and running on your local machine, you will first need to install the dependencies by running the following commands

```

Create enviroment file (.env) to set DB username and password - 
atlas_uri=mongodb+srv://${username}:${password}@cluster0.ugy1i52.mongodb.net/pet_shield?retryWrites=true&w=majority
username and password should be mentioned in the .env file
Download all the packages and their dependencies - npm install
Run the web application - npm start

```

## Deployment

The developed feature is deployed on Netlify at URL - https://spontaneous-blancmange-9e6574.netlify.app

Backend Apis render URL -> https://pet-shield-backend.onrender.com



## Built With
* [Reactjs](https://reactjs.org/) - The web framework used to build the web app.
* [CSS](https://www.w3.org/Style/CSS/Overview.en.html) - Styling the web app. 
* [Nodejs](https://nodejs.org/en) - Open source, cross-platform runtime environment for executing JavaScript code. 
* [Netlify](https://www.netlify.com/) - Used to deploy the application on web.
* [Render](https://render.com/) - Used to deploy the backend part of the application on web.
* [Visual Studio](https://code.visualstudio.com/) - Code editor.


## Sources Used in the project

### Images used 

https://www.istockphoto.com/vector/man-is-playing-with-his-pet-dog-fetching-ball-game-scene-gm1015270310-273238016

https://www.istockphoto.com/illustrations/dog-and-owner



### code in model package

All the database oriented operations performed in the model classes were referred from https://www.mongodb.com/docs/v5.0/


### Analytics.js

*Lines 89 - 189*

The Analytics page  is created by refering to https://mui.com/material-ui/react-card/

- <!---Why---> (https://mui.com/material-ui/react-card/)'s code was referenced because it is an open source platfrom that provides way to create card efficiently. 
- <!---How---> (https://mui.com/material-ui/react-card/)'s code was modified by just using the skeleton/structure defined. All the card items inside the Analytics were individually created.

### ViewInsurances.js

*Lines 179 - 304*

The AppBar created in this page was modified by refering to https://mui.com/material-ui/react-app-bar/

- <!---Why---> (https://mui.com/material-ui/react-card/)'s code was referenced because it is an open source platfrom that provides way to create card efficiently. 
- <!---How---> (https://mui.com/material-ui/react-card/)'s code was modified by just using the skeleton/structure defined. All the card items inside the Analytics were individually created.

### Payment.js

*Lines 119 - 219*

The Payment card created in this page was modified by refering to https://react-bootstrap.github.io/components/cards/

- <!---Why---> (https://react-bootstrap.github.io/components/cards/)'s code was referenced because it is shows how to render text using Bootstrap cards component with React JS
- <!---How---> (https://react-bootstrap.github.io/components/cards/)'s code was modified by just using the skeleton/structure defined. All the content was individually created.

### ChartBar.css
The css code above was created by adapting the code in [https://chartscss.org/charts/bar/]

### RegistrationDate.css
The css code above was created by adapting the code in [https://www.cssscript.com/css-css3/]


### RegistrationDoctor.js
*Lines 106 - 145*

The Use of FormData is referenced by https://developer.mozilla.org/en-US/docs/Web/API/FormData/append
- <!---Why---> (https://developer.mozilla.org/en-US/docs/Web/API/FormData/append)'s code was referenced because it is an open source platfrom that provides way to use of FormData. 
- <!---How---> (https://developer.mozilla.org/en-US/docs/Web/API/FormData/append)'s code was generated by learning a way of use FormData.

*Lines 119*
```
/^[^\s@]+@[^\s@]+\.[^\s@]{2,}$/i;
```
The code above was created by adapting the code in [w3resource](https://www.w3resource.com/) as shown below:
```
 let emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]{2,}$/i
```
### Login.js
*Lines 196 - 280*

The Paper like form is  created  by refering https://mui.com/material-ui/react-paper/
- <!---Why---> (https://mui.com/material-ui/react-paper/)'s code was referenced because it is an open source platfrom that provides way to create paper like form efficiently. 
- <!---How---> (https://mui.com/material-ui/react-paper/)'s code was modified by just using the skeleton/structure defined. All the items inside the paper were individually created.

### user_registrationController.js (server\src\controllers\user_registrationController.js)
*Line 142 & 384*

The use of bcrypt to hash password is leraned from https://blog.logrocket.com/password-hashing-node-js-bcrypt/
- <!---Why---> (https://blog.logrocket.com/password-hashing-node-js-bcrypt/)'s code was referenced because it is an open source platfrom that provides way to hash password for security concern. 
- <!---How---> (https://blog.logrocket.com/password-hashing-node-js-bcrypt/)'s code was modified by just using the skeleton/structure defined. All the items inside were individually created.

*Lines 240- 276*

The use of nodemailer to send mail is referenced by https://nodemailer.com/about/
- <!---Why---> (https://nodemailer.com/about/)'s code was referenced because it is an open source platfrom that provides way to learn about nodmailer to send emails. 
- <!---How---> (https://nodemailer.com/about/)'s code was modified by just using the skeleton/structure defined. All the items inside were individually created.

*Lines 256 - 275*
```
<div style="font-family: Helvetica,Arial,sans-serif;min-width:1000px;overflow:auto;line-height:2">
  <div style="margin:50px auto;width:70%;padding:20px 0">
    <div style="border-bottom:1px solid #eee">
      <a href="" style="font-size:1.4em;color: #00466a;text-decoration:none;font-weight:600">Your Brand</a>
    </div>
    <p style="font-size:1.1em">Hi,</p>
    <p>Thank you for choosing Your Brand. Use the following OTP to complete your Sign Up procedures. OTP is valid for 5 minutes</p>
    <h2 style="background: #00466a;margin: 0 auto;width: max-content;padding: 0 10px;color: #fff;border-radius: 4px;">324457</h2>
    <p style="font-size:0.9em;">Regards,<br />Your Brand</p>
    <hr style="border:none;border-top:1px solid #eee" />
    <div style="float:right;padding:8px 0;color:#aaa;font-size:0.8em;line-height:1;font-weight:300">
      <p>Your Brand Inc</p>
      <p>1600 Amphitheatre Parkway</p>
      <p>California</p>
    </div>
  </div>
</div>
```

The code above was created by adapting the code in [OTP Email Template](https://codepen.io/abhndv/pen/rNebjGo) as shown below:
```
<html>
        <div style="font-family: Helvetica,Arial,sans-serif;min-width:1000px;overflow:auto;line-height:2">
            <div style="margin:50px auto;width:70%;padding:20px 0">
              <div style="border-bottom:1px solid #eee">
                <a href="" style="font-size:1.4em;color: #00466a;text-decoration:none;font-weight:600">Pet Shield</a>
              </div>
              <p style="font-size:1.1em">Hi,</p>
              <p>Use the following OTP to reset your password.</p>
              <h2 style="background: #00466a;margin: 0 auto;width: max-content;padding: 0 10px;color: #fff;border-radius: 4px;">${_otp}</h2>
              <p style="font-size:0.9em;">Regards,<br />Pet Shield</p>
              <hr style="border:none;border-top:1px solid #eee" />
              <div style="float:right;padding:8px 0;color:#aaa;font-size:0.8em;line-height:1;font-weight:300">
                <p>Petshield</p>
                <p>Dalhosuie University</p>
                <p>Nova Scotia, Canada</p>
              </div>
            </div>
          </div>
       </html >
```
### server/src/database/database.js

*Lines 13-22*

```
const Connection = async () => {

    const URL = `mongodb+srv://${username}:${password}@cluster0.ugy1i52.mongodb.net/pet_shield?retryWrites=true&w=majority`;
    try {
       await mongoose.connect(URL, {useUnifiedTopology: true, useNewUrlParser: true})
       console.log("Database connected successfully")
    } catch (error) {
        console.log("Error connecting the database. Error : " + error)
    }
}
```

The code above was created by adapting the code in [MongoDB](https://mongoosejs.com/docs/connections.html) as shown below: 

```
mongoose.connect('mongodb://username:password@host:port/database?options...');

```

The code in [Mongodb](https://mongoosejs.com/docs/connections.html) was implemented to connect to a MongoDB database using Node.js.
The code is used to connect to a cluster hosted on MongoDB Atlas.


### code in model package

All the database oriented operations performed in the model classes were referred from https://www.mongodb.com/docs/v5.0/


### PetOwnerNavbar.js

*Lines 15 - 147*

The AppBar created in this page was modified by refering to https://mui.com/material-ui/react-app-bar/

- <!---Why---> (https://mui.com/material-ui/react-app-bar/)'s code was referenced because it is an open source platfrom that provides way to create NavBar efficiently. 
- <!---How---> (https://mui.com/material-ui/react-app-bar/)'s code was modified by just using the skeleton/structure defined. All the menu items inside the AppBar were individually created.

### VetNavbar.js

*Lines 15 - 147*

The AppBar created in this page was modified by refering to https://mui.com/material-ui/react-app-bar/

- <!---Why---> (https://mui.com/material-ui/react-app-bar/)'s code was referenced because it is an open source platfrom that provides way to create NavBar efficiently. 
- <!---How---> (https://mui.com/material-ui/react-app-bar/)'s code was modified by just using the skeleton/structure defined. All the menu items inside the AppBar were individually created.

### ServiceCards.js

*Lines 9 - 33*

The AppBar created in this page was modified by refering to https://react-bootstrap.github.io/components/cards/

- <!---Why---> (https://react-bootstrap.github.io/components/cards/)'s code was referenced because it is shows how to render text using Bootstrap cards component with React JS
- <!---How---> (https://react-bootstrap.github.io/components/cards/)'s code was modified by just using the skeleton/structure defined. All the content was individually created.

### Appointment.js

*Lines 81 - 100*

The AppBar created in this page was modified by refering to https://react-bootstrap.github.io/components/modal/

- <!---Why---> (https://react-bootstrap.github.io/components/modal/)'s code was referenced because it is shows how to render text using Bootstrap Modal component with React JS
- <!---How---> (https://react-bootstrap.github.io/components/modal/)'s code was modified by just using the skeleton/structure defined. All the content was individually created.

### Star.js

*Lines 3 - 7*

```
const Star = ({ filled }) => (
  <span style={{ color: filled ? '#ffc107' : '#e4e5e9' }}>
    &#9733;
  </span>
);

```

The code above was created by adapting the code in (https://www.toptal.com/designers/htmlarrows/symbols/black-star/) as shown below: 

```
<span>&#9733;</span>

```

- <!---How---> The code was implemented by HTML BY TOPTAL DESIGNERS
- <!---Why---> The code is used to display the star ratings of the vet.
- <!---How---> The code was modified by changing the color of the star. For example, if the rating of the vet is 4, then the first four start would have color as golden.

### client/src/components/homepage/ReviewsCarousal.js

*Lines 9-63*

```
    var items = [
        {
            name: "Paul Jenkins",
            review: "Probably the most random thing you have ever seen! My pets are happy now after the use of this website"
        },
        {
            name: "Ava Martins",
            review: "Best Service. I got from the vets that I had been to. The website has a professional approach."
        }
    ]

    function Item(props) {
        return (
            <Grid container spacing={1}
                sx={{
                    mt: 0
                }}>
                <Grid xs={12} sm={12} justify="space-between"
                    sx={{
                        margin: "auto",
                        display: 'flex',
                        justifyContent: 'center',
                        alignItems: 'center',
                        flexDirection: 'column',
                    }}>
                    <Paper sx={{
                        my: { md: 6 }, p: { xs: 3, md: 3 },
                        width: { md: '100%' },
                        height: { md: '100%' },
                        boxShadow: 0,
                        bgcolor: "#A8DFE4",
                        margin: "auto",
                        display: 'flex',
                        justifyContent: 'center',
                        alignItems: 'center',
                        flexDirection: 'column',
                        color: 'white',
                        fontWeight: 'bold'
                    }}>
                        <Typography align="center" variant="h2">{props.item.name}</Typography>
                        <br />
                        <Typography style={{ wordWrap: "break-word" }} align="center" variant='h5'>"{props.item.review}"</Typography>
                    </Paper>
                </Grid>
            </Grid>
        )
    }

    return (
        <Carousel animation='slide'>
            {
                items.map((item, i) => <Item key={i} item={item} />)
            }
        </Carousel>
    )
```

The code above was created by adapting the code in [react-material-ui-carousel](https://www.npmjs.com/package/react-material-ui-carousel) as shown below: 

```
function Example(props)
{
    var items = [
        {
            name: "Random Name #1",
            description: "Probably the most random thing you have ever seen!"
        },
        {
            name: "Random Name #2",
            description: "Hello World!"
        }
    ]

    return (
        <Carousel>
            {
                items.map( (item, i) => <Item key={i} item={item} /> )
            }
        </Carousel>
    )
}

function Item(props)
{
    return (
        <Paper>
            <h2>{props.item.name}</h2>
            <p>{props.item.description}</p>

            <Button className="CheckButton">
                Check it out!
            </Button>
        </Paper>
    )
}

```



- <!---How---> The code in [react-material-ui-carousel](https://www.npmjs.com/package/react-material-ui-carousel) was implemented by Shivang for developing a carousal for homepage.
- <!---Why---> The code in [react-material-ui-carousel](https://www.npmjs.com/package/react-material-ui-carousel) was implemented to implement a carousal in nodejs.
- <!---How---> [react-material-ui-carousel](https://www.npmjs.com/package/react-material-ui-carousel)'s Code was modified by wrapping it around other ui components.

### client/src/components/common/AdminSidebar.js

*Lines 23-68*

```
    let CustomListItem = ({ to, primary, tag }) => (
        <ListItem disablePadding
        >
            <ListItemButton
                to={to}
                selected={location.pathname.includes(to)}
            >
                <ListItemIcon>
                    {tag}
                </ListItemIcon>
                <ListItemText primary={primary} />
            </ListItemButton>
        </ListItem>
    )

    return (
        <Drawer
            variant="permanent"
            sx={{
                display: { xs: 'none', sm: 'none', md: 'block' },
                width: drawerWidth,
                flexShrink: 0,
                [`& .MuiDrawer-paper`]: { width: drawerWidth, boxSizing: 'border-box' },
            }}
        >
            <Toolbar />
            <Box sx={{ overflow: 'auto', mt: 2, color: '#1e69ba' }}>
                <List>
                    <CustomListItem to="/something" primary='Analytics' tag={<BarChartIcon />} />
                    <CustomListItem to="/something" primary='Vet Management' tag={<ManageAccountsIcon />} />
                </List>
                <List sx={{ position: 'absolute', bottom: 0, right: 0, left: 0, color: 'red' }}>
                    <Divider sx={{ borderBottomWidth: 4 }} />
                    <ListItemButton
                        to={'/something'}
                        selected={location.pathname.includes('/something')}
                    >
                        <ListItemText primary={'Logout'} sx={{ ml: 1 }} />
                        <ListItemIcon sx={{ minWidth: 0, mr: 1 }}>
                            <StartIcon />
                        </ListItemIcon>
                    </ListItemButton>
                </List>
            </Box>
        </Drawer>
    )

```

The code above was created by adapting the code in [Material UI Drawer](https://mui.com/material-ui/react-drawer/) as shown below: 

```
      <Drawer
        sx={{
          width: drawerWidth,
          flexShrink: 0,
          '& .MuiDrawer-paper': {
            width: drawerWidth,
            boxSizing: 'border-box',
          },
        }}
        variant="permanent"
        anchor="left"
      >
        <Toolbar />
        <Divider />
        <List>
          {['Inbox', 'Starred', 'Send email', 'Drafts'].map((text, index) => (
            <ListItem key={text} disablePadding>
              <ListItemButton>
                <ListItemIcon>
                  {index % 2 === 0 ? <InboxIcon /> : <MailIcon />}
                </ListItemIcon>
                <ListItemText primary={text} />
              </ListItemButton>
            </ListItem>
          ))}
        </List>
        <Divider />
        <List>
          {['All mail', 'Trash', 'Spam'].map((text, index) => (
            <ListItem key={text} disablePadding>
              <ListItemButton>
                <ListItemIcon>
                  {index % 2 === 0 ? <InboxIcon /> : <MailIcon />}
                </ListItemIcon>
                <ListItemText primary={text} />
              </ListItemButton>
            </ListItem>
          ))}
        </List>
      </Drawer>
```

- <!---How---> The code in [Material UI Drawer](https://mui.com/material-ui/react-drawer/) was implemented by Shivang for developing a sidebar for dashboards
- <!---Why---> [Material UI Drawer](https://mui.com/material-ui/react-drawer/)'s was used because it is official documentation website of material ui
- <!---How---> [Material UI Drawer](https://mui.com/material-ui/react-drawer/)'s Code was modified by using it in a different method and implementing that method for each button required.

### client/src/components/common/AdminSidebar.js

*Lines 116-119*

```
pattern: {
    value: /^[a-zA-Z0-9.!#$%&'*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$/,
    message: "Invalid Email Address"
}
```

The code above was created by adapting the code in [html5-tutorial](https://html5-tutorial.net/form-validation/validating-email/) as shown below:

```
/^[a-zA-Z0-9.!#$%&'*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$/
```

- <!---How---> The code in [html5-tutorial](https://html5-tutorial.net/form-validation/validating-email/) was implemented by Shivang for validating the input email address to match the following REGEX
- <!---Why---> [html5-tutorial](https://html5-tutorial.net/form-validation/validating-email/)'s Code was used because REGEX are already defined to validate particular patterns.
- <!---How---> [html5-tutorial](https://html5-tutorial.net/form-validation/validating-email/)'s Code was modified by using it in the required conditions which were not mentioned on the source side.

### server/src/controllers/vet/Calendar.js

_Lines 50-61_

```

              <Calendar
                  // defaultValue={date}
                  minDate={new Date()}
                  minDetail="year"
                  value={date}
                  readOnlyInput
                  showIcon
                  showButtonBar
                  touchUI
                  onChange={(e) => {
                    setDate(e.target.value);
                  }}
                />

```

The code above was created by adapting the code in https://primereact.org/calendar/ as shown below:

```
<Calendar value={date} onChange={(e) => setDate(e.value)} />

```

- <!---Why---> (https://primereact.org/calendar/ code was referenced because it is an open source platfrom that provides way to create Calendar and add validations efficiently.
- <!---How---> (https://primereact.org/calendar/ code was modified by just adding the base components and the validations were developed from as per requirement.

### server/src/controllers/vet/AppointmentCard.js

_Lines 88-107_

```

 <Dialog open={modalflag}>
        <DialogTitle>
          Please enter the reason for cancelling the appointment
        </DialogTitle>
        <DialogContent>
          <TextField
            autoFocus
            margin="dense"
            id="name"
            label="Cancellation Reason"
            type="text"
            fullWidth
            variant="standard"
          />
        </DialogContent>
        <DialogActions>
          <Button onClick={handlemodalClose}>Cancel</Button>
          <Button onClick={handleconfirmationOpen}>Submit</Button>
        </DialogActions>
      </Dialog>


```

The code above was created by adapting the code in https://mui.com/material-ui/react-dialog/

- <!---Why---> (https://mui.com/material-ui/react-dialog/) code was referenced because it is an open source platfrom that provides way to create modal.
- <!---How---> (https://mui.com/material-ui/react-dialog/) code was modified by just adding the behavior implemented by calling the functions as per the user action(input).

### server/src/controllers/vet/AppointmentDetails.js

_Lines 70-106_

```

const StyledProfile = styled.div`
  width: 400px;
  height: 500px;
  border-radius: 60px;
  margin: 0rem auto;
  position: relative;
  overflow: hidden;
  box-shadow: 0px 0px 5px 2px #ccc;
  display: flex;
  flex-direction: column;
  .profile-top {
    height: 50%;
    width: 100%;
    position: absolute;
    background: linear-gradient(
      360deg,
      rgba(30, 105, 186, 1) 19%,
      rgba(0, 212, 255, 1) 100%
    );
    border-radius: 60px;
  }


```

The code above was created by adapting the code in https://styled-components.com/docs/advanced#theming as shown below:

```

const Button = styled.button`
  font-size: 1em;
  margin: 1em;
  padding: 0.25em 1em;
  border-radius: 3px;

  /* Color the border and text with theme.main */
  color: ${props => props.theme.main};
  border: 2px solid ${props => props.theme.main};
`;

```

- <!---Why---> (https://styled-components.com/docs/advanced#theming code was referenced because it is an open source platfrom that provides way to create styled components nested within other components.
- <!---How---> (https://styled-components.com/docs/advanced#themingcode was referred and then developed based on the styling that was needed to be implemented.


## Acknowledgments

* [Material UI](https://mui.com/material-ui/) for providing useful and handy render components for react js
* [React JS](https://reactjs.org/) Framework for documentation.
* [React Bootstrap](https://react-bootstrap.github.io/)
* [React Router] (https://reactrouter.com/docs/en/v6/getting-started/overview) - React router is used for page routing in React application.
* [Google Fonts] https://fonts.googleapis.com/css2?family=Merriweather+Sans&family=Roboto+Slab&display=swap - Font used in the navigation bar design.
* [JQuery] https://ajax.googleapis.com/ajax/libs/jquery/3.6.1/jquery.min.js
* [Prime React] https://www.npmjs.com/package/react-datepicker - Prime React Calendar is used to select date for add and viewing appointments.
* [Npm Axios] https://www.npmjs.com/package/axios


## Other Image References Used for the website development

[1]practo.com, 2023. https://www.practo.com/ [Accessed March 04, 2023].

[2]w3schools.com, 2023. https://www.w3schools.com/css/css_boxmodel.asp  [Accessed March 04, 2023].

[3]udemy.com, 2023. https://udemy.com/course/react-the-complete-guide  [Accessed March 04, 2023].

[4]imagecolorpicker.com, 2023. https://imagecolorpicker.com/en [Accessed March 04, 2023].

[5]Chart.org, 2023. https://chartscss.org/charts/bar/ [Accessed March 04, 2023].

[6]Vcacanada.com, 2023. https://vcacanada.com/carecentre/-/media/vca-canada/images/hospitals/canada/alberta/carecentre/staff/700x525_care_smith.jpg?h=525&w=700&la=en&hash=DC7893BABD38D9A8AE8518550DC4F393 [Accessed February 06, 2023].

[7]Milduravet.com.au, 2023. https://milduravet.com.au/wp-content/uploads/2022/03/katherine-overs-profile.jpg [Accessed February 06, 2023].

[8]Vcahospitals.com, 2023. https://vcahospitals.com/-/media/2/vca/images/hospitals/united-states/california/marina/staff/700x525_marinaca_blancar.ashx?h=525&iar=0&w=700&hash=2AFBA3F221E1A971519D3368E9DBF492 [Accessed February 06, 2023].

[9]Unsplash.com, 2023. https://images.unsplash.com/photo-1629909613654-28e377c37b09?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8Y2xpbmljfGVufDB8fDB8fA%3D%3D&w=1000&q=80 [Accessed February 06, 2023].


