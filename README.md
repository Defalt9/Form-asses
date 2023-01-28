<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>Front-end foundations: HTML forms</title>
    <link
      href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.min.css"
      rel="stylesheet"
      type="text/css"
    />
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <main>
      <form>
          <div>
            <label for="name">Name:</label>
            <input
              id="name"
              type="text"
              name="name"
            />
          </div>
          <div>
            <label for="Email">Email:</label>
            <input
              id="name"
              type="text"
              name="Email"
              required
            />
          </div>
        <div>
          <label for="form-message">Your message:</label>
          <textarea
            id="form-message"
            name="message"
            required
            maxlength="200"
            
          ></textarea>
        </div>
        <button type="submit">Submit</button>
      </form>
    </main>
  </body>
</html>
