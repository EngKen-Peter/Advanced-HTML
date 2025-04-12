<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
</head>
<body>
    <!-- Header section containing the main title -->
    <header>
        <h1>Welcome to My Website</h1>
    </header>

    <!-- Navigation menu -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#list">List</a></li>
            <li><a href="#contacts">Contacts</a></li>
            <li><a href="#registration">Registration</a></li>
        </ul>
    </nav>

    <!-- Main content section -->
    <main>
        <!-- Roman numeral list section -->
        <section id="list">
            <h2>Our Services</h2>
            <ol type="I">
                <li>Web Development</li>
                <li>Mobile Applications</li>
                <li>Cloud Solutions</li>
                <li>Digital Marketing</li>
                <li>Cybersecurity</li>
            </ol>
        </section>

        <!-- Image section -->
        <section>
            <h2>Featured Image</h2>
            <img src="https://images.pexels.com/photos/1181671/pexels-photo-1181671.jpeg" 
                 alt="Person using laptop with code on screen" 
                 width="600" 
                 height="400">
        </section>

        <!-- Contacts table section -->
        <section id="contacts">
            <h2>Contact Directory</h2>
            <table border="1">
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Address</th>
                        <th>Mobile</th>
                        <th>Email</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Porsche GT3RS</td>
                        <td>123 Main St, City</td>
                        <td>555-0101</td>
                        <td>porschegt3rs@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Dennis Muloma</td>
                        <td>456 Oak Ave, Town</td>
                        <td>555-0102</td>
                        <td>dennismuloma@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Purity Kwamboka</td>
                        <td>789 Pine Rd, Village</td>
                        <td>555-0103</td>
                        <td>puritykwamboka@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Eric Mweu</td>
                        <td>321 Elm St, County</td>
                        <td>555-0104</td>
                        <td>ericmweu@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Lorna Mwende</td>
                        <td>654 Maple Dr, State</td>
                        <td>555-0105</td>
                        <td>lornamwende@gmail.com</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <!-- Registration form section -->
        <section id="registration">
            <h2>Registration Form</h2>
            <form action="#" method="POST">
                <!-- Personal Information -->
                <fieldset>
                    <legend>Personal Information</legend>
                    
                    <div>
                        <label for="name">Full Name:</label>
                        <input type="text" id="name" name="name" required 
                               placeholder="Enter your full name">
                    </div>

                    <div>
                        <label for="email">Email:</label>
                        <input type="email" id="email" name="email" required 
                               placeholder="Enter your email">
                    </div>

                    <div>
                        <label for="password">Password:</label>
                        <input type="password" id="password" name="password" required 
                               minlength="8" placeholder="Minimum 8 characters">
                    </div>

                    <div>
                        <label for="birthdate">Date of Birth:</label>
                        <input type="date" id="birthdate" name="birthdate" required>
                    </div>
                </fieldset>

                <!-- Preferences -->
                <fieldset>
                    <legend>Preferences</legend>
                    
                    <div>
                        <label for="course">Select Course:</label>
                        <select id="course" name="course" required>
                            <option value="">Choose a course</option>
                            <option value="web">Web Development</option>
                            <option value="mobile">Mobile Development</option>
                            <option value="cloud">Cloud Computing</option>
                            <option value="ai">Artificial Intelligence</option>
                        </select>
                    </div>

                    <div>
                        <p>Preferred Study Time:</p>
                        <input type="radio" id="morning" name="study_time" value="morning">
                        <label for="morning">Morning</label>
                        
                        <input type="radio" id="afternoon" name="study_time" value="afternoon">
                        <label for="afternoon">Afternoon</label>
                        
                        <input type="radio" id="evening" name="study_time" value="evening">
                        <label for="evening">Evening</label>
                    </div>

                    <div>
                        <p>Areas of Interest:</p>
                        <input type="checkbox" id="frontend" name="interests" value="frontend">
                        <label for="frontend">Frontend Development</label>
                        
                        <input type="checkbox" id="backend" name="interests" value="backend">
                        <label for="backend">Backend Development</label>
                        
                        <input type="checkbox" id="database" name="interests" value="database">
                        <label for="database">Database Management</label>
                    </div>
                </fieldset>

                <button type="submit">Register</button>
                <button type="reset">Reset Form</button>
            </form>
        </section>
    </main>

    <!-- Footer section -->
    <footer>
        <p>Contact us at: <a href="kennedymbaluka23@gmail.com">kennedymbaluka23@gmail.com</a></p>
        <p>&copy; 2025 Advanced HTML5 Demo. All rights reserved.</p>
    </footer>
</body>
</html>
