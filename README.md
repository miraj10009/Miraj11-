# Miraj11-
<!DOCTYPE html>
<html>
  <head>
    <title>School Admission Form</title>
  </head>
  <body>
    <h1 align="center">School Admission Form</h1>

    <form>
      <table border="1" align="center" cellpadding="1">
        <tr>
          <td>Name:</td>
          <td><input type="text" placeholder="First Name" /></td>
          <td><input type="text" placeholder="Last Name" /></td>
        </tr>

        <tr>
          <td >Father's Name:</td>
          <td><input type="text" placeholder="First Name" /></td>
          <td><input type="text" placeholder="Last Name" /></td>
        </tr>

        <tr>
          <td>Mother's Name:</td>
          <td><input type="text" placeholder="First Name" /></td>
          <td><input type="text" placeholder="Last Name" /></td>
        </tr>

        <tr>
          <td>Phone Number:</td>
          <td colspan="3"><input type="tel" placeholder="Phone Number" /></td>
        </tr>

        <tr>
          <td>Email:</td>
          <td colspan="3"><input type="email" placeholder="Email Address" /></td>
        </tr>

        <tr>
          <td>Date of Birth:</td>
          <td colspan="2"><input type="date" /></td>
        </tr>

        <tr>
          <td>Address:</td>
          <td><input type="text" placeholder="Village" /></td>
          <td><input type="text" placeholder="City" /></td>
        </tr>

        <tr>
          <td>Gender:</td>
          <td colspan="2">
            <input type="radio" name="gender" value="male" /> Male
            <input type="radio" name="gender" value="female" /> Female
          </td>
        </tr>

        <tr>
          <td>GPA:</td>
          <td>
            <select>
              <option>A+</option>
              <option>A</option>
              <option>A-</option>
              <option>B</option>
              <option>C</option>
              <option>D</option>
            </select>
          </td>
          <td><input type="text" placeholder="GPA Point" /></td>
        </tr>

        <tr>
          <td>Subjects:</td>
          <td colspan="2">
            <input type="checkbox" value="Islamic History" /> Islamic History
            <input type="checkbox" value="English" /> English
            <input type="checkbox" value="Math" /> Math
          </td>
        </tr>

        <tr>
          <td colspan="3" align="center">
            <input type="submit" value="Submit" />
          </td>
        </tr>
      </table>
    </form>
  </body>
</html
