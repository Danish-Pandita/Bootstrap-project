
<! DOCTYPE HTML>
<html>
  <head>
    <meta char="utf-8">
    <title>Bootstrap Basics</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <style>
      body {
        background-color: yellow;
      }
      .btn-danger{
        background-color:gray;
      }
    </style>
  </head>
  <body>
    <h1>Bootstrap Basics</h1>
    <button class="btn btn-danger btn-lg">CLICK ME</button>
    <button class="btn btn-success btn-lg" disabled>CLICK ME</button>
    <button class="btn btn-success btn-lg" active>CLICK ME</button>
    <a href="https://getbootstrap.com/docs/3.3/css/" class="btn btn-info btn-lg">BOOTSTRAP</a>
      <div class="container">
    <div class="jumbotron">
      <h1>JUMBOTRON</h1>
      
      </div>
        <form>
  <div class="form-group">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" placeholder="Email">
  </div>
  <div class="form-group">
    <label for="exampleInputPassword1">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
  </div>
  <div class="form-group">
    <label for="exampleInputFile">File input</label>
    <input type="file" id="exampleInputFile">
    <p class="help-block">Example block-level help text here.</p>
  </div>
  <div class="checkbox">
    <label>
      <input type="checkbox"> Check me out
    </label>
  </div>
  <button type="submit" class="btn btn-default">Submit</button>
</form>
      
    </div>
    
  </body>
</html>
