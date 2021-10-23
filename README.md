## Mass Unfollower for twitter

# unfollow entitled fuckers who dont follow you back in twitter

Unfollow (stop following) those people who are not following you back on Twitter (or unfollow everyone if desired).<br>
	
This will work for new Twitter web site code structure (it was changed from July 2019, causing other unfollow-scripts to stop working).<br>
	
## Instructions:
1. The code may need to be modified depending on the language of your Twitter web site:
	* For English language web site, no modification needed.
	* For Spanish language web site, remember to set the 'LANGUAGE' variable to "ES".
	* For another language, remember to set the 'LANGUAGE' variable to that language and modify the 'WORDS' object to add the words in that language.
2. Optionally, you can edit the 'SKIP_USERS' array to insert those users that you do not want to unfollow (even if they are not following you back).
3. If you want to follow everyone (except the users in 'SKIP_USERS'), including those who are following you, just set the 'UNFOLLOW_FOLLOWERS' variable to 'true'.
4. You can set the milliseconds per cycle (each call to the 'performUnfollow' function) by modifying the 'MS_PER_CYCLE' variable.
5. If desired, set a number to the 'MAXIMUM_UNFOLLOW_ACTIONS_PER_CYCLE' variable to establish a maximum of unfollow actions to perform for each cycle (each call to the 'performUnfollow' function). Set to null to have no limit.
6. If desired, set a number to the 'MAXIMUM_UNFOLLOW_ACTIONS_TOTAL' variable to establish a maximum of unfollow actions to perform in total for all cycles (all calls to the 'performUnfollow' function). Set to null to have no limit.
7. When the code is fine, on Twitter web site, go to the section where it shows all the people you are following (https://twitter.com/YOUR_USERNAME_HERE/following).
8. Once there, open the JavaScript console (F12 key, normally), paste all the code there and press enter.
9. Wait until you see it has finished. If something goes wrong or some users were not unfollowed, reload the page and repeat from the step 8 again.	

* Gist by Joan Alba Maldonado: https://gist.github.com/jalbam/d7678c32b6f029c602c0bfb2a72e0c26