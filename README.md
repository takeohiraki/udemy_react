# Noodle Calendar

<h1>Goal</h1>
<h3>Slack for Calendars. Encouraging productivity and continuity in our calendars</h3>

<p>Fundamental idea #1: meetings require as much, if not more continuity and organization than just P2P or P2Group communication, but right now most people just use hand-written notes.</p>

<p>Fundamental idea #2: many meetings are ill-prepared for or just shouldn't happen. How can we encourage behavior that would make a higher percentage of meetings worth having?</p>

<h1>Proposed Functionality</h1>
<ul>
  
  <li>Use Google Cal integration to:
    <ul>
    <li>Allow users to create and edit Calendar events</li>
    <li>Allow users to add details to calendar events</li>
    </ul>
  </li>
  
  <li>Use Heroku to:
    <ul>
      <li>Create server to route requests</li>
      <li>Create barebones Postgres DB for small-scale data</li>
    </ul>
  </li>
  
  <li>Use Slack integration to:
    <ul>
      <li>Allow users to add details to calendar events</li>
      <li>Make votes for things like cancelling meetings</li>
    </ul>
  </li>
  
</ul>
