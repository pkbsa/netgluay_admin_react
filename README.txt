<-- ### VERY IMPORTANT PART ### -->
Here are the step by step on how to run this program

<--- Setup part --->
1. open the cmd and cd the directory of "sec2_gr6_src"
2. type in
 	npm install
3. congratulation you are done setting up
PS. if you are using other os that is not Window please delete 'SET PORT' at package.json
<--- ---------- --->

<--- Run part --->
1. open the cmd and cd the directory of "sec2_gr6_src" directory
2. type `npm start` in the cmd
3. open `http://localhost:5206/dashboard`
<--- ---------- --->

<--- ID / PASSWORD for access into site --->
email : admin
password : admin
<--- ---------------------------------- --->

NetGluay : http://202.183.167.111:4206/browse
Admin: http://202.183.167.111:5206/dashboard

<-- What Phase2 file did I Updated? -->
- routes/admin
	insert/update function to hashedpassword of the user before loading it into database
	update: if the password is blank use old password otherwise use the password provide
	login-admin : I add this function to return the response if the login credential is correct
- routes/pages
	insert more pages example more movies and aboutus page
	