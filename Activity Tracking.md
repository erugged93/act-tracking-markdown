---


---

<h1 id="activity-tracking">Activity Tracking</h1>
<p><img src="https://lh3.googleusercontent.com/82MskL5ytP5IBD0Q90bx2IsGIpSX52SBrv7jyJBrs98Bz5tfqzVv6E8xOdNSVbediqw6YWxfxlaf" alt="Activity Tracking UI" title="Activity Tracking"><br>
As you can see in the screenshot, when you are on the Activity Tab, there is the possibility of a user logging an activity on the sidebar.  This becomes an issue if we wanted to try and add this logged activity to the timeline without reloading the page.<br>
We made the decision to make the load more activity functionality a Place in Time list.  It stores the time at which you load the page initially and it only ever shows activities that were logged at or before the page load.  SO now if you were to add an activity on the sidebar it would not show up until you reload the page.<br>
This makes it simpler to manage as we wont have to worry about sorting the logged activity manually into the list currently on the screen, however we would like a way of showing on this timeline view that the user logged the activity successfully and that they will have to reload the page if they want to see the new activities.<br>
Kevin came up with the idea of a floating blue banner that shifted the timeline down a little that reads<br>
<strong>There are new activities to show, <em>reload the page</em> to see them</strong> where the “reload the page” would be a tertiary link button.<br>
We wanted to get your take on the best way to show that there were new items but that it would take a refresh to see them, as we dont want a user to have clicked load more 5 times and be super far down the page and have it automatically refresh on them but still want it to be known that the logged activity didnt just vanish.<br>
<img src="https://lh3.googleusercontent.com/iZHSn3U47ZVgUMval7YqclVRppCsbphS_pKL_Jrd9qjESDsncPmTBBNQ5znZ8RPfaOqWsenN_njH" alt="enter image description here" title="With Banner"></p>

