  
# Questions: #

* **Q:** When I start my server I get a bambi timeout error and or spawn doing a fortnite tee-pose in the ground and then the server kicks me! What do I do?

* **A:** Around line 104-ish depending on your install, you will find:

**"# Set the SQL mode to strict"**

**sql-mode=STRICT_TRANS_TABLES,NO_AUTO_CREATE_USER,NO_ENGINE_SUBSTITUTION**

`**You MUST change this to:**`

**"# Set the SQL mode to strict"**

**sql-mode=""**

