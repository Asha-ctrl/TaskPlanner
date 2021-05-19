<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
   <link href="style.css" rel="stylesheet" type="text/css">
    <title>Task Planner</title>
        <!-- Option 2: Separate Popper and Bootstrap JS -->
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js" integrity="sha384-Atwg2Pkwv9vp0ygtn1JAojH0nYbwNJLPhwyoVbhoPwBhjQPR5VtM2+xf0Uwh9KtT" crossorigin="anonymous"></script>
  </head>


  <body>
    <h1>Task Planner</h1>
  <div></div> 
  <div></div>
  <br>
  <h2>Add Task</h2>
  <div class="container">
<form id="newtask">
    <div></div> 
    <div></div>
    <div class="row">
        <label type="text">Task Name</label>
        <div class="col-md-6">
          <input type="text" class="form-control" placeholder="Task Name" aria-label="Task Name" id="taskname">
          <div>
          </div>
          <div class="row">
            <label type="text">Assigned To</label>
            <div>
            <input type="text" class="form-control" placeholder="Assigned To">
          </div>
        </div>
        </div>
        <div class="row">
            <div class="col-md-6">
            <label type="text">Description</label>
          <textarea type="text" class="form-control" placeholder="Description" aria-label="Description"></textarea>
        </div>
        </div>
    </div>
<!-- Date input -->
        <div class="form-group"> 
          <label class="control-label" for="date">Due Date</label>
          <input class="form-control" id="duedate" name="Due Date" placeholder="MM/DD/YYY" type="date"/>
        </div>
    </form>

        <br>
       </form>
    <br>
       <div></div>
       <div></div>
   <select class="Status Select" aria-label="Status">
        <option selected>Status</option>
        <option value="1">To-do</option>
        <option value="2">In-progress</option>
        <option value="3">Review</option>
        <option value="4">Done</option>
      </select>
  
<br>
<br>

      <div class="form-group"> <!-- Submit button -->
        <button class="btn btn-primary " name="submit" type="submit">Submit</button>
    </form>
      </div>
    </div>
</div>
      <br>
      <br>
      <!--Task Card List-->

      <h2>Task List</h2>
      <br>
      <br>
      <!--list group-->
      <div class="container">
      <div class="accordion" id="tasklist">
        <div class="list-item">
          <h2 class="accordian-header" id="taskone">
            <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
              Attend Meeting
            </button>
          </h2>
          <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
            <div class="accordion-body">
                <div class="Tasks" style="width: 18rem;">
                    <div class="Task-body">
                      <h5 class="Task Name">Meeting</h5>
                      <h6 class="card-subtitle mb-2 text-muted">Assigned to: Loren</h6>
                      <br>
                      <p class="Description">Meeting with Jane in tht conference room.</p>
                      <h7>Due Date: 18/05/2021</h7>
                      <div></div>
                      <br>
                      <button href="#" class="card-link">To-do</button>
                      <br>
                      <br>
                      <a href="#" class="card-link">Delete</a>
                    </div>
            </div>
          </div>
        </div>
        <div class="list-item">
          <h2 class="accordion-header" id="tasktwo">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
              Clean Office
            </button>
          </h2>
          <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
            <div class="accordion-body">
                <div class="Tasks" style="width: 18rem;">
                    <div class="Task-body">
                      <h5 class="Task Name">Clean Office</h5>
                      <h6 class="card-subtitle mb-2 text-muted">Assigned to:John</h6>
                      <p class="Description">Vacuum the meeting room and tidy the kitchen.</p>
                      <h7>Due Date: 16/05/2021</h7>
                      <div></div>
                      <br>
                      <button href="#" class="card-link">Done</button>
                      <br>
                      <br>
                      <a href="#" class="card-link">Delete</a>
                    </div>
            </div>
          </div>
        </div>
        <div class="list-item">
          <h2 class="accordion-header" id="taskthree">
            <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
              Order Lunch
            </button>
          </h2>
          <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
            <div class="accordion-body">
                <div class="Tasks" style="width: 18rem;">
                    <div class="Task-body">
                      <h5 class="Task Name">Order Lunch</h5>
                      <h6 class="card-subtitle mb-2 text-muted">Assigned To</h6>
                      <p class="Description">Send everyone the menue for their lunch order and deliver it to restaurant</p>
                      <h7>Due Date: 16/05/2021</h7>
                      <div></div>
                      <br>
                      <button href="#" class="card-link">In-progress</button>
                      <br>
                      <br>
                      <a href="#" class="card-link">Delete</a>
                    </div>
            </div>
          </div>
        </div>
      </div>
      <div class="list-item">
        <h2 class="accordion-header" id="taskfour">
          <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
            Organise Computer Files
          </button>
        </h2>
        <div id="collapseFour" class="accordion-collapse collapse" aria-labelledby="headingFour" data-bs-parent="#accordionExample">
          <div class="accordion-body">
              <div class="Tasks" style="width: 18rem;">
                  <div class="Task-body">
                    <h5 class="Task Name">Organise Computer Files</h5>
                    <h6 class="card-subtitle mb-2 text-muted">Assigned to: Rose</h6>
                    <p class="Description">Make sure that all the compuer files are properly labled and organised</p>
                    <h7>Due Date: 20/05/2021</h7>
                      <div></div>
                      <br>
                      <button href="#" class="card-link">Reviw</button>
                      <br>
                      <br>
                      <a href="#" class="card-link">Delete</a>
                    </div>

                  <div class="list-item">
        <h2 class="accordion-header" id="headingfive">
          <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
            Document The Meeting
          </button>
        </h2>
        <div id="collapseFive" class="accordion-collapse collapse" aria-labelledby="headingFive" data-bs-parent="#accordionExample">
          <div class="accordion-body">
              <div class="Tasks" style="width: 18rem;">
                  <div class="Task-body">
                    <h5 class="Task Name">Task 1</h5>
                    <h6 class="card-subtitle mb-2 text-muted">Assigned to: Sharon</h6>
                    <p class="Description">Take notes during the meeting and send meeting minutes to everyone.</p>
                    <h7>Due Date: 20/05/2021</h7>
                    <div></div>
                    <br>
                    <button href="#" class="card-link">Done</button>
                    <br>
                    <br>
                    <a href="#" class="card-link">Delete</a>
                  </div>
  
      </div>
      </div>
      <footer>
          <br>
          <br>
      </footer>
  </body>
</html>
