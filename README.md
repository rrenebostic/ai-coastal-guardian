# ai-coastal-guardian

*Model Context Protocol (MCP) server connecting Claude AI to NOAA tide data with AI Agent workflows for automated coastal environmental condition alerts.*

![AI Coastal Guardian Data Flow by Rene Bostic_2025](https://github.com/user-attachments/assets/dc28f6aa-11bd-46a4-ba12-565972249341)


## The AI Coastal Guardian Project ##

*Leveraging Claude AI, NOAA Tide Data through the Model Context Protocol (MCP) with integrated AI Agents for Enhanced Beach Experiences*

<br/>

## Project Overview ##

The AI Coastal Guardian Project aims to transform your coastal adventures by combining the intelligence of Claude AI with real-time National Oceanic and Atmospheric Administration (NOAA) tide data. This project implements a Model Context Protocol (MCP) server that enables Claude AI to access and interpret oceanic information, enabling a more coordinated and efficient response to the issues caused by sargassum accumulation. Additionally, AI Agents will be utilized to automate email alerts to the public.

No more arriving at the beach only to find unfavorable environmental conditions (See image below). In the near future, the AI Coastal Guardian Project will help you plan the perfect coastal getaway by providing intelligent insights with predictions and alerts when conditions pose a high health risk.

For more details about the launch of the project visit [Medium.com](https://medium.com/@renebostic/wave-hello-to-stress-free-coastal-getaways-with-ai-beach-buddies-claude-ai-noaa-tides-mcp-server-35716624bcc7).

![Photo by Rene Bostic_2025 South Beach Miami Spring Break 2025_Seaweed Bloom](https://github.com/user-attachments/assets/16d47160-311c-4908-baff-49d4844d06ee)

<br/>

## Key Features ##

•	**Real-Time Tide Information:** Access current tide data from NOAA's extensive network of coastal stations

•	**Intelligent Activity Planning:** Receive personalized recommendations for the best times to visit beaches for specific activities

•	**Natural Language Interface:** Interact with tide data through Claude's conversational AI

•	**Location-Aware:** Find nearby tide stations and get localized information

•	**Safety First:** Get safety alerts about potentially dangerous tide conditions

•	**Seaweed Bloom Alerts:** Receive automated email notifications about seaweed bloom predictions

•	**AI Agent Workflows:** Leverage an AI Agent Workflow Automation tool for orchestrating Claude AI and NOAA data integrations

<br/>

## How It Works ##

The AI Coastal Guardian Project leverages Anthropic's Model Context Protocol (MCP) to connect Claude AI with NOAA's Tides and Currents data system:

1.	**MCP Server:** The core of the project is an MCP server that interfaces between Claude AI and NOAA's tide data APIs
2.	**NOAA Integration:** The server communicates with NOAA's Tides and Currents API to retrieve real-time water level data, tide predictions, and station information
3.	**Intelligent Processing:** The system applies algorithms to interpret tide data and generate activity recommendations
4.	**Claude AI Interface:** Users interact with the system through natural language conversations with Claude
5.	**AI Agent Workflow Automation:** AI Agent workflows to orchestrate the integration between Claude AI and the NOAA Tides MCP Server
6.	**Automated Alerting:** The system monitors for conditions that may lead to seaweed blooms and sends email alerts via Gmail

<br/>

## Example Interactions ##

•	"What are the tide conditions at Malibu Beach tomorrow?"

•	"When is the best time to go surfing in San Diego this weekend?"

•	"Is it safe to take kids tide pooling at La Jolla Cove on Saturday morning?"

•	"I'm planning a beach picnic at Coronado Beach. What time should I avoid?"

•	"What's the best beach near me for shell collecting based on current tide conditions?"

•	"Can you alert me if there's a risk of seaweed blooms at Miami Beach this week?"

•	"Set up weekly tide reports for my local beach by email."

<br/>

## Technical Implementation ##

The AI Coastal Guardian Project uses several key technologies:

•	**Model Context Protocol (MCP):** Enables Claude AI to access external data sources and tools

•	**NOAA CO-OPS API:** Provides access to water level data, tide predictions, and station metadata

•	**Python FastMCP Framework:** Simplifies MCP server implementation

•	**Claude AI:** Powers the natural language understanding and response generation

•	**JSON:** Used for the integration between Claude Desktop and NOAA Tides MCP Server

•	**AI Agent Workflow Automation:** Integrates Claude AI and NOAA Tides MCP Server prediction capabilities within an AI Agent workflow

•	**Email Integration:** Generates and sends automated seaweed bloom alerts via Gmail

<br/>

## NOAA Data Integration ##

The project connects to several NOAA data endpoints:

•	**Water Level Measurements:** Real-time and historical water levels

•	**Tide Predictions:** Future tide predictions for planning

•	**Water Temperature:** Real-time and forecasted ocean temperature data

•	**Station Metadata:** Information about tide stations including location and capabilities

•	**Nearby Station Search:** Finding relevant tide stations based on geolocation

<br/>

## Getting Started ##

The implementation requires a specific technical configuration. This approach leverage no-code/low-code methods:

**Step 1:** Install the [Claude for Desktop](https://support.anthropic.com/en/articles/10065433-installing-claude-for-desktop).

**Step 2:** [Ryan Cardin](https://github.com/RyanCardin15) is acknowledged for creating the most automated method for installing the NOAA Tides MCP Server. Install the NOAA Tides MCP Server for the Claude Desktop using [Smithery](https://smithery.ai/server/@RyanCardin15/noaa-tidesandcurrents-mcp).

*note:* If the Smithery server is down and your project is urgent, the NOAA Tides and Currents MCP Server installation instructions can be found on [MCP Market](https://mcpmarket.com/server/noaa-tides-and-currents).

**Step 3:** Switch to the Claude Desktop. From the toolbar, select Settings -> Developer -> Edit Config. 

**Step 4:** Navigate to Rayan Cardin's Smithery page and click on the JSON tab to copy the JSON script.

**Step 5:** Paste the copied JSON script into your editor.

**Step 6:** Close the Claude Desktop.  Reopen. You will now see the noaa-tidesandcurrents listed. 

<img width="563" alt="Integration of Claude AI with NOAA Tides MCP Server v2" src="https://github.com/user-attachments/assets/6ddff57e-3f4f-4cb5-a7ab-d20465473827" />


**Step 7:** Use the prompt "What information is provided from NOAA Tides?"   Claude AI responds with several thought-provoking questions.

<br/>

## Future Enhancements ##

•	Integration with weather data for comprehensive beach planning

•	Mobile app for on-the-go tide checking

•	Image recognition for beach conditions from user photos

•	Crowd sourcing of real-time beach conditions from users

•	Integration with beach safety warnings and surf conditions

•	Expansion of the AI Agent workflows to include additional data sources and alerts

•	Advanced seaweed bloom prediction using machine learning models

•	Integration with smart home systems for automated morning beach reports

<br/>

## Sample Output ##  

### Prompt ###  

**Summary:**  Claude AI communicates with the noaa-tidesandcurrents MCP Server via JSON scripts.  You can prompt Claude in natural language or directly using JSON.  Communicating with Claude via JSON was confirmed via a prompt.  See image below. 

<img width="774" alt="AI Coastal Guardian_JSON Prompt" src="https://github.com/user-attachments/assets/6b1d7a67-74d2-413b-b653-279ed3475a16" />

<br/>

<br/>

**Prompt 1:** What is the water temperature at station id 8724580?

**Observation 1:**  Claude leverages the NOAA tides data via the noaa-tidesandcurrents MCP Server.  Claude’s first attempt is to determine the correct JSON script necessary to retrieve the requested information.  Once Claude is successful, it provides a comprehensive answer.  See image below.  

<img width="765" alt="AI Coastal Guardian_Water Temperature Prompt" src="https://github.com/user-attachments/assets/5b46f025-0b67-4125-a700-625c1d4531a9" />


<br/>

<br/>

**Prompt 2:**  Is the weather conducive for seaweed bloom?

**Observation 2:**  Claude responded in three (3) parts: 

***Part 1 Observation:***  To answer the question, Claude “reasoned” and determined it required (1) both meteorological and ocean data, and (2) multiple factors that influence seaweed bloom including water temperature, nutrient, levels, wind patterns, and ocean currents.  See response below.

<img width="758" alt="AI Coastal Guardian_Seaweed Conditions Part 1" src="https://github.com/user-attachments/assets/8eecb71e-bd00-451d-b374-9f13f4f38306" />

<br/>

<br/>

***Part 2 Observation:*** Claude provides a synopsis  of the water temperature, air temperature, wind conditions, and water levels at Station 8724580.  See response below.

<img width="734" alt="AI Coastal Guardian_Seaweed Conditions Part 2" src="https://github.com/user-attachments/assets/75c8623f-08de-4c2f-9881-ab3d1c38b41a" />

<br/>

<br/>

***Part 3 Observation:*** Claude justifies reaching its conclusion. Details regarding its justification are important when validating the accuracy of the response. See response below.

<img width="761" alt="AI Coastal Guardian_Seaweed Conditions Part 3" src="https://github.com/user-attachments/assets/5f7421dc-d3c0-46c9-bb69-60ace9c94236" />

<br/>

<br/>

**Prompt 3:**  Please write an email to Miami Citizen about the water temperature at station id 8723214. . The tone should be respectful but urgent. Include if the water temperature is conducive for seaweed bloom. The email should be short put complete.

**Observation:** Claude leverages the NOAA tides data and its email writing capabilities to craft the email. After several iterations the following email was generated by Claude. See image below. 

<img width="701" alt="AI Coastal Guardian_email for Station ID 8723214" src="https://github.com/user-attachments/assets/6646bb64-e191-4eb7-8b10-ec01847a5578" />

<br/>

<br/>

**Conclusion:** These are my initial findings.

<br/>

## Sample AI Workflow to Identify Seaweed Bloom Conditions and Create an SMS Alert ##  

### The AI Workflow Prompt ###  

**Lessons Learned**  As I explored different prompts for Claude AI to access NOAA data using either a natural language prompt versus JSON scripts, I determined that incorporating the JSON script directly into the prompt was much more efficient. Below is an example when using a natural language prompt only without a JSON script.  You will notice that Claude AI iterates to generate the optimal JSON script.

<br/>

<img width="648" alt="Claude AI accessing the NOAA Tides MCP Server via Natural Language v2" src="https://github.com/user-attachments/assets/5fb7d312-3139-49d8-8f5e-bcc32d4ceef1" />

<br/>

<br/>

Using a natural language prompt can lead to unnecessary processing time, which can increase carbon emissions. Therefore, incorporating the JSON script directly into the prompt is much more environmentally friendly and produces faster response times. Let’s review the prompt I used to create the SMS text alert.

The goal is to create an AI Workflow to combine the tasks of identifying conditions for seaweed bloom and sending an SMS message to beachgoers.  Therefore, the prompt utilizes a two-step workflow to create distinct processing phases that significantly improve output quality.

<img width="760" alt="Workflow Prompt 1" src="https://github.com/user-attachments/assets/e5138983-5f3e-4eed-85f8-aa732d13c22c" />

<br/>

<br/>

**<Step 1>:** Data Acquisition Parameters: The precise specification of the NOAA data source (Station ID 8723214), data product (water_temperature), and format (JSON) established clear technical boundaries for the initial environmental assessment phase, eliminating ambiguity in data source selection.

**<Step 2>:** Character-Constrained Optimization: The explicit 160-character limitation for the SMS alert created a well-defined technical constraint that forced algorithmic optimization of message content while maintaining critical information density.

<br/>

### CLAUDE AI STEP 1 ###

<img width="761" alt="Workflow Step 1" src="https://github.com/user-attachments/assets/3c41de7c-b9d5-43e9-ae65-2a6d4bc79774" />

<br/>

<br/>

Immediately, you notice how easily and much faster Claude AI communicated via the NOAA tides and currents API using the JSON script. This technical determination included:

1. Comparative Threshold Analysis: The 83.7°F reading exceeds the established 80°F threshold for accelerated seaweed growth by 4.6%, placing it firmly within high-probability conditions for bloom formation.
  
2. Temporal Context Implementation: The May 15th timestamp positions this reading during a seasonal transition period known to correlate with increased nutrient availability, further amplifying bloom probability when combined with elevated temperatures.
  
3. Geospatial Parameter Consideration: Virginia Key’s position (25.7314, -80.1618) represents a monitoring location with established historical correlation to broader coastal conditions affecting Miami’s recreational beaches.

<br/>

### CLAUDE AI STEP 2 ###


<img width="769" alt="Workflow Step 2" src="https://github.com/user-attachments/assets/b2548090-cc12-4bc4-b542-f45c66b8f7e6" />

<br/>

<br/>

Claude AI utilized a multi-layered processing pipeline optimized for both information density and character conservation to generate the following 160-character SMS text alert:

_ALERT: High-risk for seaweed bloom at Virginia Key today! Avoid respiratory/skin irritation risks. Skip the beach — explore Vizcaya Museum’s gardens instead! #StaySafe_

Note that I did not recommend an alternative vacation activity. Claude AI made the determination. If there are specific city-sponsored events, including that information in the prompt would be helpful. Another step could include iterating on the text message to note Miami Beach as the location versus the Virginia Key station.

**Conclusion of AI Workflow**  Once the integration between Claude AI and the NOAA Tides and Currents MCP Server is established, you can begin ideation and testing scenarios. This specific AI Workflow was easier to create than expected.  The next goal is to automate the alerts using and AI Agent.

<br/>

## Learn More ##

This project was born from a passion for both AI technology and beach activities. Read more about the development journey and technical details by subscribing to [René Bostic Medium articles](https://medium.com/@renebostic/subscribe).

<br/>

## Resources ##

•	[NOAA Tides and Currents]( https://tidesandcurrents.noaa.gov/)

•	[Anthropic’s Claude AI]( https://www.anthropic.com/claude)

•	[Model Context Protocol]( https://modelcontextprotocol.io/introduction)

•	[n8n Workflow Automation]( https://n8n.io/)

•	[Gmail API Documentation]( https://developers.google.com/gmail/api/guides)


•	[Securing Generative AI for Dummies](https://www.netskope.com/resources/ebooks/securing-generative-ai-for-dummies)

<br/>

## License ##
This project is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0)
License - see the LICENSE file for details.
 
Made with ❤️ by Rene Bostic
