# Platester
## SEI Project 3
 
**A Team coded full stack app**

Deployed here - [platester](https://platester.herokuapp.com/)

Project Members

[Issra Hashim](https://github.com/IssraHashim)
[Mariah Gilling](https://github.com/msgilling)
[Lee Wiseman](https://github.com/leewiseman94)

The third project I completed as part of my SEI course is my first attempt at a full stack app and the first time working in a group. We had 1.5 weeks to complete this project. 

Platester is an Airbnb clone that’s an online recipe resource where users can upload, edit and delete their own recipes as well as comment and rate other users recipes. Users are also able to “like” recipes and save these to their profile.

**Brief**

Requirements

- Create a full stack app
- Must have multiple models and relationships with CRUD functionality
- 8 days to complete
- Should use Node.js, Express & MongoDB

Technologies Used

- MongoDB
- Node.js
- JWT
- Bcrypt
- React.js
- Axios
- Bulma
- CSS
- React Router Dom

**Planning**

From the start of the project, as a group we decided that we would meet twice daily for a stand up once in the morning to discuss the day ahead and then once in the evening to make sure any merge conflicts were fixed immediately. We also kept Zoom open all day so we could ask advice of team members at any time.

We decided that we would code the backend together after which we individually coded frontend elements. We wireframed the app and made a relationships diagram before splitting the components between us. I looked after the  Homepage, Footer and CookingClasses. Issra did the Authentication, Reviews, AddRecipe, UpdateRecipe and Inspirations that she pair coded with Mariah. As well as Inspirations, Mariah created the RecipeIndex and RecipeShow pages. Lee handled the UserProfile, Navbar and filtering.

<img width="1016" alt="wireframe" src="https://user-images.githubusercontent.com/91135210/169501429-7aba0f39-f27e-47f7-a68d-56f7bee2fbbb.png">
<img width="801" alt="relationships" src="https://user-images.githubusercontent.com/91135210/169501520-e6f870ec-6419-4173-a95a-5c05eed6a179.png">

**Process**

We took it in turns whilst screen sharing to code the back end. This worked well as we were able as a group to spot errors and find solutions to issues quickly. Whilst doing this we also planned out the models routes and controllers we’d need for the app.

As this was full stack we needed to create our own database of recipes to draw from. So we set about seeding our db with recipe data. Then we checked the db was running using Insomnia.

Once we’d finished the backend we concentrated on the frontend components we’d been assigned. As we were attempting to clone Airbnb, I wanted to get some data from our db so we could display 3 recipes as Bulma cards on the Homepage along side a hero image and some other cards to act as links to other components within the app.

![platester](https://user-images.githubusercontent.com/91135210/169501111-7b8f878e-322a-4bac-836a-7e19552b5d7e.png)

In order to the data for the cards (with help from the team), I wrote some code to populate 3 cards for starter, main and dessert courses.

![Screenshot 2022-05-20 at 11 01 22](https://user-images.githubusercontent.com/91135210/169505012-2677a449-ddeb-4823-9b96-1c2e8d8290bc.png)


With the courses now up and running it was a case of finding images online and creating the image boxes and cards for the rest of the page.

![front page](https://user-images.githubusercontent.com/91135210/169502487-cf0efb45-ca1f-45a9-bb8e-590f158700ac.png)
![front page](https://user-images.githubusercontent.com/91135210/169502546-37d1974c-a52e-43ca-b166-8b1ce85baeeb.png)

Once the home page had been completed it was onto the footer. Again using Bulma, I simply duplicated the format from Airbnb.

The CookingCourses component was also pretty quick. I created a simple page and populated it with some cooking videos from Youtube.

<img width="838" alt="Screenshot 2022-01-13 at 17 01 06" src="https://user-images.githubusercontent.com/91135210/169502836-5ba3f825-18d0-4dec-8dc8-53150b277b8c.png">

**Wins & Challenges**

I found the logic for getting the individual courses to display very hard. Fortunately as I was working with such a fantastic team, I was able to collaboratively find a solution. Also Bulma ended up being a bit of a struggle as we had to do a lot of extra CSS work to get exactly what we wanted.

The major win was working in a larger group. This was brilliant for me and it was great learning from my teammates. I was also really happy about how the finished app turned out. I think it’s a pretty decent facsimile of Airbnb!
