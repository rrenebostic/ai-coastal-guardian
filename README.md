# ai-coastal-guardian

*Model Context Protocol (MCP) server connecting Claude AI to NOAA tide data with AI Agent workflows for automated coastal environmental condition alerts.*

![AI Coastal Guardian Data Flow by Rene Bostic_2025](https://github.com/user-attachments/assets/dc28f6aa-11bd-46a4-ba12-565972249341)




## The AI Coastal Guardian Project ##

*Leveraging Claude AI, NOAA Tide Data through the Model Context Protocol (MCP) with integrated AI Agents for an Enhanced Beach Experiences*

## Project Overview ##

AI Coastal Guardian Project aims to transform your coastal adventures by combining the intelligence of Claude AI with real-time NOAA tide data. This project implements a Model Context Protocol (MCP) server that enables Claude AI to access and interpret oceanic information, providing you with personalized recommendations for your beach visits. Additionally, AI Agents will be utilized to automate email alerts for seaweed blooms and other coastal conditions.

No more arriving at the beach only to find unfavorable tide conditions for your planned activities. In the near future, the AI Coastal Guardian Project will help you plan the perfect coastal getaway by providing intelligent insights about the peak of seawood bloom and safety recommendations.

## Key Features ##

•	**Real-Time Tide Information:** Access current tide data from NOAA's extensive network of coastal stations

•	**Intelligent Activity Planning:** Receive personalized recommendations for the best times to visit beaches for specific activities

•	**Natural Language Interface:** Interact with tide data through Claude's conversational AI

•	**Location-Aware:** Find nearby tide stations and get localized information

•	**Safety First:** Get safety alerts about potentially dangerous tide conditions

•	**Seaweed Bloom Alerts:** Receive automated email notifications about seaweed bloom predictions

•	**AI Agent Workflows:** Leverage an AI Agent Workflow Automation tool for orchestrating Claude AI and NOAA data integrations

## How It Works ##

The AI Coastal Guardian Project leverages Anthropic's Model Context Protocol (MCP) to connect Claude AI with NOAA's Tides and Currents data system:

1.	**MCP Server:** The core of the project is an MCP server that interfaces between Claude AI and NOAA's tide data APIs
2.	**NOAA Integration:** The server communicates with NOAA's Tides and Currents API to retrieve real-time water level data, tide predictions, and station information
3.	**Intelligent Processing:** The system applies algorithms to interpret tide data and generate activity recommendations
4.	**Claude AI Interface:** Users interact with the system through natural language conversations with Claude
5.	**AI Agent Workflow Automation:** AI Agent workflows to orchestrate the integration between Claude AI and the NOAA Tides MCP Server
6.	Automated Alerting: The system monitors for conditions that may lead to seaweed blooms and sends email alerts via Gmail

## Example Interactions ##

•	"What are the tide conditions at Malibu Beach tomorrow?"

•	"When is the best time to go surfing in San Diego this weekend?"

•	"Is it safe to take kids tide pooling at La Jolla Cove on Saturday morning?"

•	"I'm planning a beach picnic at Coronado Beach. What time should I avoid?"

•	"What's the best beach near me for shell collecting based on current tide conditions?"

•	"Can you alert me if there's a risk of seaweed blooms at Miami Beach this week?"

•	"Set up weekly tide reports for my local beach by email."


## Technical Implementation ##

The AI Coastal Guardian Project uses several key technologies:

•	**Model Context Protocol (MCP):** Enables Claude AI to access external data sources and tools

•	**NOAA CO-OPS API:** Provides access to water level data, tide predictions, and station metadata

•	**Python FastMCP Framework:** Simplifies MCP server implementation

•	**Claude AI:** Powers the natural language understanding and response generation

•	**JSON:** Used for the integration between Claude Desktop and NOAA Tides MCP Server

•	**AI Agent Workflow Automation:** Integrates Claude AI and NOAA Tides MCP Server prediction capabilities within an AI Agent workflow

•	**Email Integration:** Generates and sends automated seaweed bloom alerts via Gmail

## NOAA Data Integration ##

The project connects to several NOAA data endpoints:

•	**Water Level Measurements:** Real-time and historical water levels

•	**Tide Predictions:** Future tide predictions for planning

•	**Water Temperature:** Real-time and forecasted ocean temperature data

•	**Station Metadata:** Information about tide stations including location and capabilities

•	**Nearby Station Search:** Finding relevant tide stations based on geolocation

## Getting Started ##

The implementation requires a specific technical configuration. This approach leverage no-code/low-code methods:

**Step 1:** Install the [Claude for Desktop](https://support.anthropic.com/en/articles/10065433-installing-claude-for-desktop).

**Step 2:** [Ryan Cardin](https://github.com/RyanCardin15) is acknowledged for creating the most automated method for installing the NOAA Tides MCP Server. Install the NOAA Tides MCP Server for the Claude Desktop using [Smithery](https://smithery.ai/server/@RyanCardin15/noaa-tidesandcurrents). I used the default setting for the port and transportType and set the applicationName to "NOAA-MCP-Server."

**Step 3:** Switch to the Claude Desktop. From the toolbar, select Settings -> Developer -> Edit Config. 

**Step 4:** Navigate to Rayan Cardin's Smithery page and click on the JSON tab to copy the JSON script.

**Step 5:** Paste the copied JSON script into your editor.

**Step 6:** Close the Claude Desktop.  Reopen. You will now see the noaa-tidesandcurrents listed. 

![Integration of Claude AI with NOAA Tides MCP Server](https://github.com/user-attachments/assets/5c482e55-fafc-44d3-8412-8cefe8380594)


**Step 7:** Use the prompt "What information is provided from NOAA Tides?"   Claude AI responds with several thought-provoking questions.

## Future Enhancements ##

•	Integration with weather data for comprehensive beach planning

•	Mobile app for on-the-go tide checking

•	Image recognition for beach conditions from user photos

•	Crowd sourcing of real-time beach conditions from users

•	Integration with beach safety warnings and surf conditions

•	Expansion of the AI Agent workflows to include additional data sources and alerts

•	Advanced seaweed bloom prediction using machine learning models

•	Integration with smart home systems for automated morning beach reports

## Learn More ##

This project was born from a passion for both AI technology and beach activities. Read more about the development journey and technical details in the full blog post.

## Resources ##

•	[NOAA Tides and Currents]( https://tidesandcurrents.noaa.gov/)

•	[Anthropic’s Claude AI]( https://www.anthropic.com/claude)

•	[Model Context Protocol]( https://modelcontextprotocol.io/introduction)

•	[n8n Workflow Automation]( https://n8n.io/)

•	[Gmail API Documentation]( https://developers.google.com/gmail/api/guides)

## License ##
This project is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0)
License - see the LICENSE file for details.
 
Made with ❤️ by Rene Bostic
