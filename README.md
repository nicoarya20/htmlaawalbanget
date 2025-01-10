<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HTML Cheat Sheet</title>
  </head>
  <body>
    <!-- Headings -->
    <h1>Heading One</h1>
    <h2>Heading Two</h2>
    <h3>Heading Three</h3>
    <h4>Heading Four</h4>
    <h5>Heading Five</h5>
    <h6>Heading Six</h6>

    <a href="blog.html">Go To My Blog</a>

    <!-- Paragraphs -->
    <p>
      Lorem ipsum, dolor sit amet consectetur adipisicing elit. Delectus ipsum
      repellendus adipisci sunt <strong> incidunt. Quam provident </strong> fuga
      aliquid velit adipisci, <em>quo veritatis expedita ipsa</em> deleniti
      molestiae assumenda beatae! Eveniet, non.
    </p>
    <p>
      Lorem ipsum,
      <a href="https://www.google.com/" target="_blank">dolor sit amet</a>
      consectetur adipisicing elit. Delectus ipsum repellendus adipisci sunt
      incidunt. Quam provident fuga aliquid velit adipisci, quo veritatis
      expedita ipsa deleniti molestiae assumenda beatae! Eveniet, non.
    </p>

    <!-- Lists -->
    <ul>
      <li>List Item One</li>
      <li>List Item Two</li>
      <li>List Item Three</li>
      <li>List Item Four</li>
    </ul>
    <ol>
      <li>List Item One</li>
      <li>List Item Two</li>
      <li>List Item Three</li>
      <li>List Item Four</li>
    </ol>

    <!-- Tables -->
    <table>
      <thead>
        <tr>
          <th>Name</th>
          <th>Email</th>
          <th>Age</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Nico</td>
          <td>nico@gmail.com</td>
          <td>24</td>
        </tr>
        <tr>
          <td>Putra</td>
          <td>putra@gmail.com</td>
          <td>23</td>
        </tr>
        <tr>
          <td>Putri</td>
          <td>putri@gmail.com</td>
          <td>21</td>
        </tr>
      </tbody>
    </table>
    <br />
    <hr />
    <br />
    <!-- Forms -->
    <form action="process.php" method="POST">
      <div>
        <label>First Name</label>
        <input type="text" name="first-name" placeholder="Enter First Name" />
      </div>
      <br />
      <div>
        <label>Last Name</label>
        <input type="text" name="last-name" placeholder="Enter Last Name" />
      </div>
      <br />
      <div>
        <label>Email</label>
        <input type="email" name="email" placeholder="Enter Email" />
      </div>
      <br />
      <div>
        <label>Message</label>
        <textarea name="message"></textarea>
      </div>
      <br />
      <div>
        <label>Gender</label>
        <select name="gender">
          <option value="male">Male</option>
          <option value="female">Female</option>
          <option value="other">Other</option>
        </select>
      </div>
      <br />
      <div>
        <label>Age :</label>
        <input type="number" name="age" value="30" />
      </div>
      <br />
      <div>
        <label>Birthday :</label>
        <input type="date" name="birthday" />
      </div>
      <br />
      <input type="submit" value="Submit" name="submit" />
    </form>

    <!-- Buttons -->
    <button>Click Me</button>
    <br />
    <!-- Images -->
    <a href="images/crow.jpg">
      <img
        src="images/crow.jpg"
        alt="My Sample Image"
        width="200"
        height="200"
      />
    </a>
    <br />
    <!-- Quotes-->
    <blockquote cite="https://google.com">
      Lorem ipsum dolor, sit amet consectetur adipisicing elit. Labore
      voluptatem magnam, obcaecati nihil saepe magni quisquam eius eligendi
      totam similique dolore doloribus natus quae impedit officia, fugiat iure
      beatae pariatur.
    </blockquote>
    <br />
    <p>
      The <abbr title="Worl Wide Web">WWW</abbr> is the best thing since sliced
      bread
    </p>
    <br>
    <p>HTML Course by Me<cite> is very easy peasy lemon squissy</cite></p>

    <div style="margin-top: 50px"></div>
  </body>
</html>
