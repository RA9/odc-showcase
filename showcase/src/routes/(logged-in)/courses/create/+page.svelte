<svelte:head>
	<title>Create Course</title>
</svelte:head>


<main>
    <h2 class="display-4 text-uppercase text-center mt-4">Create Course</h2>
	<div class="container-fuild">
		<div class="container my-5">
			<div class="row">
				<div class="col-lg-8 mx-auto">
					<div class="card shadow-sm">
						<div class="card-body">
							<div class="text-center">
								<h4 class="card-title mb-4">Want to enroll?</h4>
								<p class="card-text mb-4">Click the link below to enroll in Course_Name:</p>
								<a href="#" class="">https://web.facebook.com/?_rdc=1&_rdr</a>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="container my-5">
			<div class="row">
				<div class="col-lg-8 mx-auto">
					<div class="card shadow-sm">
						<div class="card-body">
							<h2 class="card-title text-center mb-4">Introduction to Course Name</h2>

							<h5 class="card-subtitle mb-3 text-muted">Course Description:</h5>
							<div class="form-group mb-4">
								<textarea class="form-control" rows="5" id="course-description" />
							</div>
							<ul class="list-group mb-3">
								<li class="list-group-item">
									<label for="start-date">Duration:</label>
									<input type="text" id="duration" class="form-control" />
								</li>
								<li class="list-group-item">
									<label for="start-date">Location:</label>
									<input type="text" id="location" class="form-control" />
								</li>
								<li class="list-group-item">
									<label for="start-date">Instuctor:</label>
									<input type="text" id="instuctor" class="form-control" />
								</li>
								<li class="list-group-item">
									<label for="start-date">Start Date:</label>
									<input type="date" id="start-date" class="form-control" />
								</li>
								<li class="list-group-item">
									<label for="end-date">End Date:</label>
									<input type="date" id="end-date" class="form-control" />
								</li>
							</ul>
							<div class="text-left">
								<a href="#" class="btn btn-primary">Create Course</a>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</main>
