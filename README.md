<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

        <h1>Create Your Account</h1>
        <h6 style="color: red;">*Required information</h6>
        <h3 style="background-color: aliceblue;">Basic information</h3>
        <form action="http://google.com" align="center">
            <table align="center">
                <tr>
                    <td align="right"><label for="Email" align="center">Email <label for="star" style="color: red;">*</label></label></td>
                    <td><input type="email" name="Email" id="Email" required autofocus></td>
                </tr>
                <tr>
                    <td align="right"><label for="password">Password <label for="star" style="color: red;">*</label></label></label></td>
                    <td><input type="password" name="password" id="password" required></td>
                </tr>
                <tr>
                    <td align="right"><label for="password">Retype Password <label for="star" style="color: red;">*</label></label></label></td>
                    <td><input type="password" name="password" id="password" required></td>
                </tr>
                <tr>
                    <td align="right"><label for="name">First Name <label for="star" style="color: red;">*</label></label></label></td>
                    <td><input type="text" name="name" id="name" required></td>
                </tr>
                <tr>
                    <td align="right"><label for="lname">Last Name <label for="star" style="color: red;">*</label></label></label></td>
                    <td><input type="text" name="lname" id="lname" required> </td>
                </tr>
                <tr>
                    <td align="right"><label for="number">Phone Number <label for="star" style="color: red;">*</label></label></label></td>
                    <td><input type="tel" name="number" id="number" required maxlength="12" placeholder="999-999-9999"> </td>
                </tr>
                <tr>
                    <td align="right"><label for="Address">Address <label for="star" style="color: red;">*</label></label></label></td>
                    <td><input type="text" name="Address" id="Address" required> </td>
                </tr>
                <tr>
                    <td align="right"><label for="City">City <label for="star" style="color: red;">*</label></label></label></td>
                    <td><input type="text" name="City" id="City" required> </td>
                </tr>
                <tr>
                    <td align="right"><label for="Provience">Provience <label for="star" style="color: red;">*</label></label></label></td>
                    <td><input list="Provience" required placeholder="Alberta">
                    <datalist id="Provience">
                        <option value="Alberta"></option>
                        <option value="California"></option>
                        <option value="Verginia"></option>
                        <option value="Colarado"></option>
                    </datalist> </td>
                </tr>
                <tr>
                    <td align="right"><label for="Country">Country <label for="star" style="color: red;">*</label></label></label></td>
                    <td><input type="text" name="Country" id="Country" required> </td>
                </tr>
            </table> 
            <h3 style="background-color: aliceblue;" align="left">Education</h3>
            <table align="center">
                <tr>
                    <td align="right"><label for="School">School <label for="star" style="color: red;">*</label></label></label></td>
                    <td><input type="text" name="School" id="School" required> </td>
                </tr>
                <tr>
                    <td align="right"><label for="Program">Program <label for="star" style="color: red;">*</label></label></label></td>
                    <td><input type="text" name="Program" id="Program" required> </td>
                </tr>
                <tr>
                    <td align="right"><label for="Graduate">Education Level <label for="star" style="color: red;">*</label></label></label></td>
                    <td><input type="text" name="Graduated" id="Graduate"></td>
                </tr>
                <tr align="left">
                    <td></td>
                    <td>
                        <form action="">
                            <fieldset><legend align="left">Education Status</legend>
                                <input type="radio" name="Graduated" id="Graduated">
                                <label for="Graduated">Graduated</label><br>
                                <input type="radio" name="Graduated" id="Graduated">
                                <label for="Graduated">Current Enrolled</label><br>
                                <input type="radio" name="Graduated" id="Graduated">
                                <label for="Graduated">Did Not Graduate</label>
                            </fieldset>

                        </form>
                    </td>
                </tr>
                <tr>             
                    <td align="right"><label for="Graduation">Graduation Date </label></label></label></td>
                    <td><input type="text" name="Graduation" id="Graduation" required> </td>
                </tr>
            </table>
            <h3 style="background-color: aliceblue;" align="left">Work Experience</h3>
            <table align="center" >
                <tr>
                    <td align="right"><label for="Employer">Employer <label for="star">:</label></label></label></td>
                    <td><input type="text" name="Employer" id="Employer" required> </td>
                </tr>
                <tr>
                    <td align="right"><label for="Job">Job Title <label for="star">:</label></label></label></td>
                    <td><input type="text" name="Job" id="Job" required> </td>
                </tr>
                <tr>
                    <td align="right"><label for="Duty">Job Duty<label for="star">:</label></label></label></td>
                    <td><textarea name="Duty" id="Duty" cols="20" rows="5"></textarea> </td>
                </tr>
                <tr>
                    <td align="right"><label for="Year">Worked Year <label for="star">:</label></label></label></td>
                    <td><input type="number" name="Year" id="Year" required> </td>
                </tr>
            </table>
            <h3 style="background-color: aliceblue;" align="left">Attachments</h3>
            <form action="" align="center">
                <table align="center">
                    <tr>
                        <td><label for="Attachments">Attachments <label for="Attachments">:</label></label></td>
                        <td><input type="file" name="Attachments" id="Attachments" required></td>
                    </tr>
                </table>
            </form>
            <table align="center">
                <tr>
                    <td><input type="reset" name="" id="" style="background-color: red;"></td>
                   <td> <button align="center" style="background-color: red;">apply</button></td>
                </tr>
            </table>


    </form>
</body>
</html>
