# Retriever Routes: Custom Routing Engine & GIS Integration

An advanced campus navigation platform for UMBC that replaces standard OSRM protocols with a high-precision, custom-engineered **Google Routes API** integration within the Leaflet ecosystem.

## My Personal Engineering Contributions
* **Custom Routing Engine Architecture:** Independently wrote a custom `L.Routing.Router` for the Leaflet Routing Machine (LRM) framework. This implementation replaced the default OSRM engine with the **Google Routes API**, significantly enhancing navigation accuracy and route reliability across the UMBC campus.
* **Complex API Integration & Parsing:** Engineered the logic to parse and reformat diverse **Google Directions API** responses, ensuring seamless data flow into the Leaflet UI and itinerary components.
* **Semantic Maneuver & Icon Mapping:** Developed a comprehensive conditional logic system to map Google’s vast array of maneuvers and instructions to specific UI icons, ensuring a professional and consistent user experience.
* **Multi-Modal Navigation Logic:** Implemented the "Travel Mode" switching functionality, enabling users to toggle between optimized instructions for **driving, walking, and cycling** with real-time route recalculation.

## Technical Engineering Highlights
* **GIS Middleware Engineering:** Demonstrated deep proficiency in **Leaflet.js** by extending core classes to handle custom routing requests, coordinate normalization, and itinerary formatting.
* **Data Transformation:** Built a robust logic layer to translate raw Google Routes JSON payloads into structured objects required for the frontend visualization.

***

This was a collaborative capstone project at UMBC. While the overall application was built by a team, the backend routing engine, API transformation logic, and maneuver mapping described above were written by Brian Noutchang.

**[View My Contributions Here](https://github.com/lynasberaich/retriever-routes/commits?author=noutch11)**
