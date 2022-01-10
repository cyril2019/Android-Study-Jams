# Movie Listing app

**Problem statement**
During the pandemic people at home may find it difficult to find movies to watch and entertain themselves.

**Solution**
An app that lists the most popular movies that have been released recently. The users can also see the movie’s trailers and reviews in the app.
<div style="flex;width=100%">
<img src="https://user-images.githubusercontent.com/57187039/148744184-5c5ec254-5af0-4d2f-9ebc-af1d686ff154.png" width=23%>
<img src="https://user-images.githubusercontent.com/57187039/148744207-873dc8ad-17f1-4d9b-9135-1f3be7efad1a.png" width=23%>
<img src="https://user-images.githubusercontent.com/57187039/148744218-f28de357-447a-408d-be49-b7f3bd41e99d.png" width=23%>
<img src="https://user-images.githubusercontent.com/57187039/148744229-04ee678c-097e-4315-84cd-67e1c8ef1217.png" width=23%>
</div>

**Functionality and Concept used:**
Users can see all the latest movies on the home screen. Here we are using a recycler view to display the movies. The movie details are fetched using retrofit api call.
Users can click on a movie to see more details about the movie. We use navigation to navigate from home activity to the movie info activity. When a user clicks on a movie title the user id navigates to the movie detail screen where we get more details about that movie with the help of retrofit api call.
In the movie detail screen the user can see a movie poster with the movie name and rating. Below that there are 2 recycler views scrolling in horizontal direction. First recycler view displays all the movie trailers and the second recycler view displays all the movie reviews.
When the user clicks on a youtube trailer thumbnail the user can watch the trailer in the app itself. 

**Application Link**
Github Project link: ASJ Project
APK link: APK Link

**Future Scope**
In the future we can improve the UI of the app and also add some more features like filter movies and also tell the users on which platform they can watch the movie on.
