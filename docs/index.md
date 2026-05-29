# Welcome to the HPI Maker Universe

<iframe style="width: 100%; aspect-ratio: 16/9;" src="https://www.youtube.com/embed/fNnn5ffy3VQ?si=VLjfPeU7Q5ZKBqJY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Find us here

<link rel="stylesheet" href="https://unpkg.com/leaflet@1.9.4/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet@1.9.4/dist/leaflet.js"></script>
<div id="map" style="width: 100%; height: 400px;"></div>

<script>
  const lat = 52.39355020272297;
  const lng = 13.130211482658197;
  const popupText = "Maker Universe<br>Hasso Plattner Institute - Building K<br>Prof.-Dr.-Helmert-Str. 2-3, Potsdam<br><a href='https://maps.google.com/?q=52.39364435349783,13.130208663342067' target='_blank'>Get Directions</a>";

  const map = L.map('map',{
    gestureHandling: true      // requires two fingers on touch devices
  }).setView([lat, lng], 17);

  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    attribution: '&copy; <a href="https://www.openstreetmap.org/copyright">OpenStreetMap</a> contributors'
  }).addTo(map);

  L.marker([lat, lng])
    .addTo(map)
    .bindPopup(popupText)
    .openPopup();
</script>

<style>
  .leaflet-pane,
  .leaflet-top,
  .leaflet-bottom {
    z-index: 1 !important;
  }
</style>

You can find us on the ground floor of Building K at the Hasso Plattner Institute in Potsdam. We’re right next to the main entrance, so you can’t miss us! If you plan to travel by public transport, the nearest stop is **S-Bahnhof Griebnitzsee**. From there, it’s not even a 5-minute walk to our studios.

## Here’s how to get started

### Access & Usage
- **Opening Hours**: All studios are open from 9:30 to 19:30. You’re welcome to come in, explore, and build.
- **Tool Access**: Before using any tools or machines, please watch the tutorial videos, agree to the terms of usage, and confirm your understanding of safety rules on the tablet next to each machine. 
- **Fabman**: If you want to operate safety-critical machines (like the laser cutter or soldering station), you are required to create a Fabman account and watch the corresponding tutorial videos. This is a one-time process that ensures you understand how to use the equipment safely and effectively. (Checkout the [Hardware Studio](./studios/hardware-studio.md) page for more details.)

### [Workshops](./workshops/workshops.md): Join, Show Up, Give Back
- **Registration Opens One Week Before**: All workshops are announced in the #maker-community channel on Slack. Sign-ups open exactly one week before each workshop.
- **Can’t Make It? Please Cancel**: If you are on the list but cannot attend, it’s highly important that you cancel your spot via Confluence. If you don’t, no one from the waiting list can join—which is not only bad for us, but especially unfair to fellow students.
- **Feedback Is Required**: After each workshop, we ask one simple feedback question. It’s quick, but crucial. Think of it as your participation fee—your feedback helps us keep improving!

### Materials & Projects
- **Studio Materials**: You can use all freely available materials in the studios.
- **Personal Materials**: Bring your own if needed. Partnered projects (e.g., Bachelor or research projects) may receive support for special orders.
- **Storage**: In the Project Studio, you can store project materials in labeled boxes for ongoing use.

### Sessions & Support
- **Need Help?**: Request a Drop-In Session via Slack. Once scheduled, the team will announce it so others can join.
- **Want to Share Something?**: Let us know if you want to host a session—whether it’s about a tool, a method, or something you're excited about.

### Studio Culture
- Respect the Space & Each Other:
Always clean up your workspace when you're done. Put away tools, materials, and coffee cups. Even small messes add up. We cannot clean up after you, and the cleaning team only cleans if all surfaces are cleared.
- Be Curious: Don’t worry if you’re not an expert. Drop-In Sessions are for learning, observing, or jumping in.
- Stay Safe: If you’re unsure about how something works, just ask. We’re here to help.