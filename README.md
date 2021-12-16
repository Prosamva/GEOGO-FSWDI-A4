# Assignment 4 - Creating an API Server for Blogs using Node.js &amp; MongoDB
### Full Stack Web Development Internship
#### GEOGO Techsolutions Pvt. Ltd.<br><br>

The structure of the data is defined by the following schema:

    {
    	title:   String,
    	author:  String,
    	content: String,
    	date: {type: Date, default: Date.now},
    	hidden: {type: Boolean, default: false}
    }

#### API calls:
- `/`<br>**GET**: Default message
- `/posts`<br>**GET**: To get all posts or filtered results with query parameters(title, author).<br>**POST**: To post new blog.
- `/posts/:id`<br>**GET**: Get single post by its ID.<br>**PUT**: Update single post by its ID.<br>**DELETE**: Delete single post by its ID.
<br><br><br>

> #### Tasks to implement:
> 1. Create API to get details of a single Post. ✅
> 2. Create API to update a Post. ✅
> 3. Create API to delete a Post. ✅
