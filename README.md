<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
</head>
<body>

  <h1>🎵 Spotify Dashboard</h1>

  <h2>🎯 Project Objective</h2>
  <p>The objective of this project is to create an <strong>interactive dashboard</strong> that analyzes Spotify streaming data, providing insights into <strong>top artists, tracks, and listening trends</strong> over time. This allows users to explore music patterns globally and regionally, helping with decision-making and marketing strategies.</p>

  <h2>📊 Dataset Used</h2>
  <p>The dashboard uses Spotify streaming data including <strong>track names, artist names, dates, and musical characteristics</strong>.</p>

  <h2>❓ Questions Addressed</h2>

  <h3>💡 Overall Performance & Engagement</h3>
  <ul>
    <li>What is the total number of streams for a specific track or artist?</li>
    <li>What is the average stream count per day, month, or year?</li>
    <li>What is the average popularity, danceability, and energy of the music being streamed?</li>
    <li>Which tracks have the highest number of streams?</li>
  </ul>

  <h3>👥 Audience Insights</h3>
  <ul>
    <li>How has the stream count for a specific track or artist changed over time?</li>
    <li>What are the most streamed artists and tracks?</li>
    <li>What is the distribution of streams across different months or years?</li>
  </ul>

  <h3>🎶 Music Attributes</h3>
  <ul>
    <li>What is the average energy percentage of the music being streamed?</li>
    <li>What is the average danceability and acousticness of the tracks?</li>
    <li>What are the key attributes (like popularity, loudness, and speechiness) of a specific song?</li>
  </ul>

  <h2>🛠️ Process for Analyzing the Dashboard and Identifying KPIs</h2>
  <ol>
    <li>Understand the context and overall purpose of the dashboard to grasp what data is being presented.</li>
    <li>Identify key elements such as single value metrics, charts, graphs, and tables.</li>
    <li>Connect each element to the specific questions it answers, including total streams, top tracks, top artists, and listening trends over time.</li>
    <li>Analyze patterns and trends using charts and graphs to gain insights into user behavior and music popularity.</li>
    <li>Use tables to extract detailed, track-level insights, including song characteristics and performance metrics.</li>
    <li>Summarize findings to highlight key performance indicators and actionable insights.</li>
  </ol>



  <h3>Steps Taken to Complete the Analysis</h3>
  <ol>
    <li>Connected to <code>Spotify Developers API</code> with Python (Client ID & Secret) to collect data.</li>
    <li>Stored and queried data with <code>SQL</code>.</li>
    <li>Created advanced calculations using <code>DAX</code>.</li>
    <li>Built interactive visuals with <code>Deneb</code>.</li>
    <li>Designed a responsive interface with <code>HTML</code>.</li>
    <li>Hosted and tested the project in <code>Visual Studio Code</code>.</li>
  </ol>

  <h3>Challenges & Problem Solving</h3>
  <ul>
    <li>There were no direct URLs for images in the dataset, so I used the <code>Spotify Developers API</code> to fetch images using <code>Python</code>.</li>
    <li>Integrating the images into the interactive dashboard required <code>HTML</code> for a dynamic and visually appealing display.</li>
    <li>This approach allowed me to present a complete visual experience, showing images for each artist and track alongside the data.</li>
  </ul>

  <h2>💡 Recommendations to Improve Performance</h2>

  <h3>⭐ Leverage the Strong Performance of "Blinding Lights"</h3>
  <p><strong>Insight:</strong> "Blinding Lights" by The Weeknd is a top performer in terms of stream count.</p>
  <p><strong>Recommendation:</strong> Use this song as a marketing driver by creating playlists, including it in campaigns, and analyzing its musical characteristics (BPM, energy, rhythm).</p>
  <p><strong>Impact:</strong> Maximizes visibility and helps replicate success with future content.</p>

  <h3>📈 Focus on Monthly Performance Peaks</h3>
  <p><strong>Insight:</strong> "Stream Count by Month" highlights months with peak streams.</p>
  <p><strong>Recommendation:</strong> Align releases (singles, albums, or campaigns) with these peak months.</p>
  <p><strong>Impact:</strong> Greater exposure and higher engagement.</p>

  <h3>⚡ Promote High-Energy Content</h3>
  <p><strong>Insight:</strong> The "65% Energy" metric indicates high-energy tracks dominate streaming.</p>
  <p><strong>Recommendation:</strong> Focus on producing rhythmic, lively tracks and curating high-energy playlists.</p>
  <p><strong>Impact:</strong> Boosts listener satisfaction and retention.</p>

  <h3>🎤 Analyze Content from Top-Performing Artists</h3>
  <p><strong>Insight:</strong> Top performers like The Weeknd are highlighted.</p>
  <p><strong>Recommendation:</strong> Study their music beyond streams—analyze audio features, genres, lyrical themes, and production styles.</p>
  <p><strong>Impact:</strong> Guides creation or curation of content aligned with audience demand.</p>

</body>
</html>
