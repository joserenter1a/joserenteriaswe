# Current Projects

## LandscAIpe

[LandscAIpe](https://landscaipeapp.com/) is an Expo/React Native mobile application for AI-powered landscaping design and contractor matching. [Live Now on the app store!](https://apps.apple.com/us/app/landscaipe/id6754616615) It targets iOS and Android, backed by Supabase (PostgreSQL + Edge Functions + Storage) and Google Gemini for image generation.|

<table><tr>
<td><img src=../landscaipe.png height=700px width=600px style='border-radius: 50px;'></td>
<td style='padding-left: 2rem; vertical-align: top;'>
<h2>Tech Stack</h2>
<table>
<tbody>
<tr><td>Mobile</td><td>Expo 54, React Native 0.81, React 19</td></tr>
<tr><td>Language</td><td>TypeScript (src/) + JavaScript (legacy screens/)</td></tr>
<tr><td>Backend</td><td>Supabase (PostgreSQL, Auth, Storage, Edge Functions)</td></tr>
<tr><td>AI / Image Gen</td><td>Google Gemini </td></tr>
<tr><td>Analytics</td><td>PostHog (events + session tracking)</td></tr>
<tr><td>Error Tracking</td><td>Sentry (with session replay)</td></tr>
<tr><td>Payments</td><td>Stripe (contractor billing), react-native-iap (DIY Pro)</td></tr>
<tr><td>Push</td><td>Expo Notifications</td></tr>
<tr><td>Auth</td><td>Email/Password, Google Sign-In, Apple Sign-In</td></tr>
</tbody>
</table>
</td>
</tr></table>


## DataFusion Plan Visualizer
- An interactive web application for visualizing query plans produced by Apache DataFusion. Write SQL against uploaded tables and inspect how DataFusion's query planner decomposes it into a tree of relational operators — across all four plan representations.
- [Live Demo](https://datafusion-plan-visualizer.vercel.app/)
- [Github Repository](https://github.com/joserenter1a/datafusion_plan_visualizer)

<table><tr>
<td><img src=../visualizer.png height=800px width=600px style='border-radius: 10px;'></td>
<td style='padding-left: 2rem; vertical-align: top;'>
<table>
<tbody>
<tr><td>Query Engine</td><td>Apache DataFusion</td></tr>
<tr><td>Columnar Format</td><td>Apache Arrow via PyArrow</td></tr>
<tr><td>Data Wrangling</td><td>pandas 3.0</td></tr>
<tr><td>Async API Layer</td><td>FastAPI + Uvicorn</td></tr>
<tr><td>Graph Rendering</td><td>cytoscape.js</td></tr>
<tr><td>Deployment</td><td>Vercel</td></tr>
</tbody>
</table>
</td>
</tr></table>


## WIP: JrLytics
- A mini OLAP database engine built in Python. JrLytics implements segment-based columnar storage with metadata-driven query optimization on top of Apache DataFusion.
- [Github Repository](https://github.com/joserenter1a/jrlytics)