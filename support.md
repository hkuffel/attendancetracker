# Having Issues? Drop Us a Line!
<style>
    .btn {
      display: inline-block;
      margin-bottom: 1rem;
      color: rgba(255, 255, 255, 0.7);
      background-color: rgba(255, 255, 255, 0.08);
      border-color: rgba(255, 255, 255, 0.2);
      border-style: solid;
      border-width: 1px;
      border-radius: 0.3rem;
      transition:color 0.2s, background-color 0.2s, border-color 0.2s
  }

  .btn:hover {
      color: rgba(255, 255, 255, 0.8);
      text-decoration: none;
      background-color: rgba(255, 255, 255, 0.2);
      border-color:rgba(255, 255, 255, 0.3)
  }
</style>
<div class="container">
  <div class="row header">
    <h3>Fill out the form below to learn more!</h3>
  </div>
  <div class="row body">
    <form action="#">
      <ul>
        <li>
          <p class="left">
            <label for="first_name">first name</label>
            <input type="text" name="first_name" placeholder="John" />
          </p>
          <p class="pull-right">
            <label for="last_name">last name</label>
            <input type="text" name="last_name" placeholder="Smith" />      
          </p>
        </li>
        <li>
          <p>
            <label for="email">email <span class="req">*</span></label>
            <input type="email" name="email" placeholder="john.smith@gmail.com" />
          </p>
        </li>        
        <li>
          <textarea cols="46" rows="3" name="comments"></textarea>
          <br>
          <label for="comments">comments</label>
        </li>
        <li>
          <input class="btn btn-submit" type="submit" value="Submit" />
        </li>
      </ul>
    </form>  
  </div>
</div>