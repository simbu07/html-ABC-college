# Module 6 - Day 1
# 1.  Prepare a html file to display the contents as seen in the following image
# index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <table border="1px"width="100%">
        <tbody>
                <tr>
                    <td colspan="2" align="center">
                        <strong>My Day</strong>
                    </td>

                </tr>
                <tr>
                    <td>
                        <ol>
                            <li>
                                Wake up only
                                <ul>
                                    <li>
                                        2 am
                                    </li>
                                    <li>
                                        walk
                                    </li>

                                    <li>
                                        jpg
                                    </li>
                                </ul>
                            </li>    
                        </ol>
                    </td>
                    <td rowspan="4" width="50%">
                        <table border="1px" width="50%" align="center">
                            <tr>
                                <td colspan="2" align="center">
                                    <strong>Things to Watch</strong>
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <img src="img2.jpg" width="100%">
                                </td>
                                <td>
                                    <img src="img2.jpg" width="100%">
                                </td>
                            </tr>
                            <tr>
                                <td>
                                    <img src="img2.jpg" width="100%">
                                </td>
                                <td>
                                    <img src="img2.jpg" width="100%">
                                </td>
                            </tr>
                        </table>
                    </td>
                    
                </tr>
                <tr>
                    <td>
                        <ol>
                            <li>
                                Wake up only
                                <ul>
                                    <li>
                                        2 am
                                    </li>
                                    <li>
                                        walk
                                    </li>

                                    <li>
                                        jpg
                                    </li>
                                </ul>
                            </li>
                            
                            
                        </ol>
                    </td>
                    
                </tr>
                <tr>
                    <td>
                        <ol>
                            <li>
                                Breakfast
                                <ul>
                                    <li>
                                        8 am
                                    </li>
                                    <li>
                                        eggs
                                    </li>

                                    <li>
                                        Coffee
                                    </li>
                                </ul>
                            </li>
                        </ol>
                    </td>                    
                </tr>
                <tr>
                    <td>
                        <ol>
                            <li>
                                Go to Saveetha Engineering college
                                <ul>
                                    <li>
                                        8 am
                                    </li>
                                    <li>
                                        attend classes
                                    </li>

                                    <li>
                                        to be continued
                                    </li>
                                </ul>
                            </li>
                        </ol>
                    </td>                
                </tr>

                
        </tbody>

        
    </table>
</body>
</html>

```
# Output:
![image_2024-07-04_000837851](https://github.com/simbu07/html-ABC-college/assets/94525786/d86410f7-d2f3-4af6-9f4a-cfd6171c8c20)

# <p> 2. Design a website for a College. There should be at least 15 web-pages present in the web-site. There should be:

college-website/
├── index.html
├── academics.html
├── admission.html
├── gallery.html
├── courses/
│   ├── computer-science.html
│   ├── mathematics.html
│   ├── english.html
│   ├── sociology.html
│   ├── economics.html
│   ├── business-management.html

└── images/
    ├── logo.png
    ├── gallery1.jpg
    ├── gallery2.jpg
    ├── gallery3.jpg
    └── gallery4.jpg

One Home page that leads to other pages. The Home page should contain the name of the college as heading along with the college logo. There should be a tab with the following links:
Home;
Academics;
Admission;
Gallery. 
 
There should be an appropriate description of the college on the home page.
 One Academics page which contains a list of all the departments present in the college Arts, Science and Commerce. The list should be a nested list, with available courses mentioned under each department. There should be a minimum of two courses under each department, (for e.g. Computer Science and Mathematics under Science, English and Sociology under Arts  and so on). Each Course entry in the list should be a HTML link that leads to a web-page totally dedicated to the course itself.
Each Course should have its own dedicated web-page. This page should contain a description about the course, a list of all the teachers taking the course and the timetable for that particular subject.
The Admission page basically contains a form that a student needs to fill up in order to take admission in the college. The form should ask all the necessary questions using appropriate form elements.
One gallery page that contains set of photos taken of the college and its students.
Please note that each web-page in this website should have the same background Image/color. The looks of each page should be similar.

# index.html :
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VIT | Site</title>
</head>
<body>
    <header>
         <img src="assets/college.jpeg" alt="logo">
        <nav>
            <ul>
                <li>
                    <a href="Home.html">Home page</a>
                </li>
                <li>
                    <a href="academics.html">Academics page</a>
                </li>
                <li>
                    <a href="admission.html">Admission page</a>
                </li>
                <li>
                    <a href="gallery.html">Gallery page</a>
                </li>
                
            </ul>
        </nav>
        <div>
            <h2>Welcome to College Name</h2>
            <p>Welcome to our esteemed institution, where we offer a holistic education experience. Our college is committed to providing quality education and fostering the intellectual and personal growth of our students.</p>
            <p>Our college offers a range of courses across Arts, Science, and Commerce streams. Explore our website to learn more about our academic offerings, admission process, and vibrant campus life.</p>
        </div>


    </header>
</body>
</html>
```
# Output:
![Screenshot 2024-07-02 225719](https://github.com/simbu07/html-ABC-college/assets/94525786/e981fd9e-0d9d-47d3-82a6-13133fb63d21)

# Home.html:
```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
</head>
<body>
    <header>
        <img src="assets/college.jpeg" alt="logo">
       <nav>
           <ul>
               <li>
                   <a href="index.html">Home page</a>
               </li>
               <li>
                   <a href="academics.html">Academics page</a>
               </li>
               <li>
                   <a href="admission.html">Admission page</a>
               </li>
               <li>
                   <a href="gallery.html">Gallery page</a>
               </li>
               
           </ul>
       </nav>
       <main>
            <dl>
                <dt><strong>RANKING AND RECOGNITION</strong></dt>
                <dd>
                    <ul>
                        <li>VIT National & Global Rankings</li>
                        <li> VIT 212th Best Institution of the world in the Engineering and Technology</li>
                        <li> VIT is one among the top 5-8 in india and within 701-800 universities of the world as per Shanghai ARWU (Academic Ranking of World Universities) 2023</li>
                    </ul>
                </dd>
            </dl>

            <dl>
                <dt><strong>RELATIONS</strong> </dt>
                <dd>
                    <ul>
                        <li>VIT has a strong international presence across the world and academic partnerships with over 440 foreign universities.</li>
                        <li> VIT provides options to study 2 years at VIT and 2 years at a partner foreign university. </li>
                        <li> One may also study a semester abroad or engage in international research collaboration activities with partners.</li>
                    </ul>
                </dd>
            </dl>

            <dl>
                <dt><strong>PLACEMENTS</strong> </dt>
                <dd>
                    <ul>
                        <li>2409+ Dream Offers, 2027+ Super Dream Offers</li>
                        <li> 873+ Dream & Super Dream Internship offers </li>
                        <li> 1798+ Regular Offers</li>
                        <li> 12508+ Over all Offers</li>
                        <li>Limca Book of Records for the 10th time for unbeatable placement records.</li>
                        <li>771 Number of Companies </li>

                    </ul>
                </dd>
            </dl>
    </main>
   
</body>
</html>
```
# Output:
![Screenshot 2024-07-02 225734](https://github.com/simbu07/html-ABC-college/assets/94525786/ec4a1f96-c50b-4621-bbb9-28d94c90429a)

# Academics.html:
```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VIT | Site</title>
</head>
<body>
    <header>
         <img src="assets/college.jpeg" alt="logo">
        <nav>
            <ul>
                <li>
                    <a href="Home.html">Home page</a>
                </li>
                <li>
                    <a href="academics.html">Academics page</a>
                </li>
                <li>
                    <a href="admission.html">Admission page</a>
                </li>
                <li>
                    <a href="gallery.html">Gallery page</a>
                </li>

                
            </ul>
        </nav>
        <div class="container">
            <h2>Academics</h2>
            <ul>
                <li>Arts
                    <ul>
                        <li><a href="courses/english.html">English</a></li>
                        <li><a href="courses/sociology.html">Sociology</a></li>
                    </ul>
                </li>
                <li>Science
                    <ul>
                        <li><a href="courses/computerScience.html">Computer Science</a></li>
                        <li><a href="courses/mathematics.html">Mathematics</a></li>
                    </ul>
                </li>
                <li>Commerce
                    <ul>
                        <li><a href="courses/economics.html">Economics</a></li>
                        <li><a href="courses/business-management.html">Business Management</a></li>
                    </ul>
                </li>
            </ul>
        </div>
        


    </header>
</body>
</html>
```
# Output:
![Screenshot 2024-07-02 225803](https://github.com/simbu07/html-ABC-college/assets/94525786/082af810-d9b0-4731-970b-00c6dc9f2e45)
# Admission.html:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VIT | Site</title>
</head>
<body>
    <header>
         <img src="assets/college.jpeg" alt="logo">
        <nav>
            <ul>
                <li>
                    <a href="Home.html">Home page</a>
                </li>
                <li>
                    <a href="academics.html">Academics page</a>
                </li>
                <li>
                    <a href="admission.html">Admission page</a>
                </li>
                <li>
                    <a href="gallery.html">Gallery page</a>
                </li>
                
            </ul>
        </nav>
        <div class="container">
            <h2>Admission Form</h2>
            <form action="/submit-admission" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required><br><br>
    
                <label for="dob">Date of Birth:</label>
                <input type="date" id="dob" name="dob" required><br><br>
    
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required><br><br>
    
                <label for="phone">Phone:</label>
                <input type="tel" id="phone" name="phone" required><br><br>
    
                <label for="address">Address:</label>
                <textarea id="address" name="address" required></textarea><br><br>
    
                <label for="department">Department:</label>
                <select id="department" name="department" required>
                    <option value="arts">Arts</option>
                    <option value="science">Science</option>
                    <option value="commerce">Commerce</option>
                </select><br><br>
    
                <label for="course">Course:</label>
                <select id="course" name="course" required>
                    <option value="english">English</option>
                    <option value="sociology">Sociology</option>
                    <option value="computer-science">Computer Science</option>
                    <option value="mathematics">Mathematics</option>
                    <option value="economics">Economics</option>
                    <option value="business-management">Business Management</option>
                </select><br><br>
    
                <input type="submit" value="Submit">
            </form>
        </div>


    </header>
</body>
</html>
```
# Output:
![Screenshot 2024-07-04 001555](https://github.com/simbu07/html-ABC-college/assets/94525786/5d271993-79f8-410b-a001-e413a1bc8161)


# Gallery.html:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VIT | Site</title>
</head>
<body>
    <header>
         <img src="assets/college.jpeg" alt="logo">
        <nav>
            <ul>
                <li>
                    <a href="Home.html">Home page</a>
                </li>
                <li>
                    <a href="academics.html">Academics page</a>
                </li>
                <li>
                    <a href="admission.html">Admission page</a>
                </li>
                <li>
                    <a href="gallery.html">Gallery page</a>
                </li>
                
            </ul>
        </nav>
        <div class="container">
            <h2>Gallery</h2>
            <div>
                <img src="assets/image1.jpeg" alt="Gallery Image 1" width="300">
                <img src="assets/image2.jpeg" alt="Gallery Image 2" width="300">
                <img src="assets/image3.jpeg" alt="Gallery Image 3" width="300">
                <img src="assets/image4.jpeg" alt="Gallery Image 4" width="300">
                <img src="assets/image5.jpeg" alt="Gallery Image 4" width="300">
                <img src="assets/image6.jpeg" alt="Gallery Image 4" width="300">
            </div>
        </div>

    </header>
</body>
</html>



```
# Output:
![Screenshot 2024-07-02 225821](https://github.com/simbu07/html-ABC-college/assets/94525786/3cdcee72-7d3d-4ffd-9cf1-95ca0c282d7f)


