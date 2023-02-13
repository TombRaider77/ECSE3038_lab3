write what each function do using html

app. get() is a function that tells the server what to do when a get request at the given route is called
the @app.get("/profile") creates the user profile that is to be used 


the post request illustrates the date, time and information about the user's profile

@app.get("/data")
@app.post("/data",status_code=201
retrieves data for the tanks and returns an array of 0 or more objects


@app.post("/data",status_code=201)
accepts the json with the Id attribute



@app.patch("/data/{id}")
allows the user to alter the data from the tanks after being posted


@app.delete("/data/{id}",status_code=204)
allows the user to delte previously posted tanks

