# TV-Show-Project-z-m

#LEVEL 100:

All episodes must be shownFor each episode, AT LEAST following must be displayed:the episode's namethe season numberthe episode numberthe episode's medium-sized imagethe episode's summary textYou should combine season number and episode number into an episode code:Each part should be zero-padded to two digits.Example: S02E07 would be the code for the 7th episode of the 2nd season. S2E7 would be incorrect.

Your page should state somewhere that the data has (originally) come from TVMaze.com, and link back to that site (or the specific episode on that site). See tvmaze.com/api#licensing.


#LEVEL 200:

Complete all requirements from Level 100Add a "live" search input:Only episodes whose summary OR name contains the search term should be displayedThe search should be case-insensitiveThe display should update immediately after each keystroke changes the input.Display how many episodes match the current searchIf the search box is cleared, all episodes should be shown.
If you have been fetching the episode data from the API, be careful not to cause many frequent requests with this search feature. The search should look through an in-memory copy of the episode list. Do not fetch the data again each time something is typed!


#LEVEL 300:

Add an Episode SelectorComplete all requirements from level 200Add a select input which allows you to jump quickly to an episode:The select input should list all episodes in the format: "S01E01 - Winter is Coming"When the user makes a selection, they should be taken directly to that episode in the listBonus: if you prefer, when the select is used, ONLY show the selected episode. If you do this, be sure to provide a way for the user to see all episodes again.
