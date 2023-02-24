
<svelte:head>
  <title>Login - ODC ShowCase</title>
</svelte:head>

<div class="p-3 m-0 border-0 bd-example">
	<div class="card mx-auto" style="width: 28rem; margin: 40px auto">
		<div class="card-body">
			<form>
				<div>
					<h5 class="text-center">ODC ShowCase Login</h5>
				</div>
				<div class="mb-3">
					<label for="exampleInputEmail1" class="form-label">Email</label>
					<input
						type="email"
						class="form-control"
						id="exampleInputEmail1"
						aria-describedby="emailHelp"
					/>
				</div>
				<div class="mb-3">
					<label for="exampleInputPassword1" class="form-label">Password</label>
					<input type="password" class="form-control" id="exampleInputPassword1" />
					<button type="submit" style="background: #fb8500; color: #000" class="btn btn-lg w-100 mt-2">Login</button> <br /><br
					/>
          <p class="text-center">or</p>
          <p class="text-center">
            <a href="/register">Create Account</a>
          </p>
				</div>
			</form>
		</div>
	</div>
</div>
