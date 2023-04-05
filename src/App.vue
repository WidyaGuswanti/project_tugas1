<template>

    <html>
        <head>
            <title>Widya</title>
        </head>
        <body>
          <h1><b>Widya's Course</b></h1>
       <img src="https://e7.pngegg.com/pngimages/391/387/png-clipart-training-computer-icons-education-skill-trainning-logo-business.png" alt="Logo" style="width:100px;height:90px;" /> 
       <h2>Description</h2>
            <p>Currently, the need for IT & computer training is very high. Because along with the times and technology, almost every work activity uses a computer as its main tool. In addition, the development of the internet has also become one of the things that makes the need to master computers and the internet even higher. This training can be a solution to improve employee performance so that it can have a good influence on the progress of the company.

The IT & computer training category that we present is divided into several training criteria, including: Information Technology Audit and Digital Marketing Strategy</p>
            <h3>Login</h3>
        <form action="/action_page.php">
            <label for="usname">Username:</label>
            <input type="text" id="usname" name="usname"><br><br>
            <label for="password">Password:</label>
            <input type="text" id="Password" name="Password"><br><br>
            <input type="submit" value="Submit">
        </form>
        <h4>Course</h4>
        <table border = "3">
            <tr>
                <th>List Course</th>
                <th>Price</th>
            </tr>
            <tr>
                <td>Information Technology Audit </td>
                <td>850000</td>
            </tr>
            <tr>
                <td>Digital Marketing Strategy</td>
                <td>1250000</td>
            </tr>
        </table>
        <form action="/action_page.php">
            <p><label for="Widya's Course">Review of Widya's Course:</label></p>
            <textarea id="w3review" name="w3review" rows="4" cols="50">Kritik Dan Saran</textarea>
            <br>
        </form>
            <h5><i>Contacts</i></h5>
                <a href="account1 link" target="_blank">Instagram</a>
                <a href="account2 link" target="_blank">WhatssApp</a>
            <h2><i>Write me a message</i></h2>
            <form>
                <input placeholder="Name"/><br>
                <input placeholder="Email"/><br>
                <textarea placeholder="Message" required ></textarea><br>
                <input type="submit" value="SEND"/> 
            </form>
        </body>
    </html>
    </template>