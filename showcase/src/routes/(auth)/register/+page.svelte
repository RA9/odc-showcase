<svelte:head>
	<title>Register - ODC ShowCase</title>
</svelte:head>

<div class="p-3 m-0 border-0 bd-example">
	<div class="card mx-auto" style="width: 28rem; margin: 40px auto">
		<div class="card-body">
			<form>
				<div>
					<h5 class="text-center">Register Account</h5>
				</div>
				<div class="mb-3">
					<label for="exampleInputUsername" class="form-label">Username</label>
					<input
						type="text"
						class="form-control"
						id="exampleInputUsername"
						aria-describedby="usernameHelp"
					/>
				</div>
				<div class="mb-3">
					<label for="exampleInputEmail" class="form-label">Email</label>
					<input type="email" class="form-control" id="exampleInputEmail" />
				</div>
				<div class="mb-3">
					<label for="exampleInputPassword" class="form-label">Password</label>
					<input type="password" class="form-control" id="exampleInputPassword" />
				</div>
				<div class="mb-3">
					<label for="exampleInputContact" class="form-label">Phone Number</label>
					<input type="text" class="form-control" id="exampleInputContact" />
				</div>
				<div class="mb-3">
					<label for="exampleInputAddrress" class="form-label">Address</label>
					<input type="address" class="form-control" id="exampleInputAddress" />
				</div>

                <div class="mb-3">
                    <button type="submit" class="btn btn-lg w-100 mt-2 btn-primary">Register</button> 
                    <p class="text-center">
                        or <br /><a href="login">Login</a>
                    </p>
                </div>
			</form>
		</div>
	</div>
</div>
