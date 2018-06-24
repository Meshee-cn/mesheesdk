#	Meshee Overview
Meshee is communications middleware that can cross operating systems. Meshee can be applied in the following scenarios：1) Large-coverage high-speed ad-hoc self-organizing networking scenarios; 2) scnearios where cellular data plan is expensive; 3) scenarios where cellular (e.g., 4G) or WiFi networks are not well covered and 4) scenarios where local communications and Internet communications needs collaboration.

When terminals are distributed over a large area, Meshee technology supports them to form a Meshee network. Without using cellular traffic, any two terminals can communicate with each other at high speed through the Meshee network. Communication in Meshee networks does not pass through Internet servers and therefore has privacy advantage naturally.
*	Meshee API is now applicable to Android (>= Android 21), IOS, linux, Windows and Linux version are in development.
*	Meshee API is based on self-developed Meshee networking and communications protocol, providing local Meshee networking service. The service works in the following two phases.
	*	Pre-communication phase：Create, discover and join Meshee networks before communication.
	*	In-communication phase：Exchange data, e.g., text, image, file and live stream in a formed Meshee network.
*	Meshee API privides all sorts of communications services, including Contact, Conversation, Message (e.g., text, image, customized type, File and live stream). Leveraging the aforementioned services, developers can develop local communication applications easily, such as:
	*	Live sharing - Sharing live stream from the Internet in Meshee networks. Currently http-flv format is supported, and the other formats are in development.
	*	File sharing - Easy transferring large-size file in Meshee networks.
	*	Goup game - Use customized message to develop all sorts of messaging for multi-people games.
	*	Social chat/collabtive work - Combine text, image and file messaging to achieve social chat/collabtive work.

#	Meshee features
Meshee has the following features.
*	Cross-OS platforms - Meshee is software middleware, which can provide cross-platform communication services.
*	Large network coverage - The underlying transferring layer of Meshee is WiFi, which makes network coverage as large as 400 meters.
*	Large number or terminals in a Meshee network - a single Meshee network can connect ~100 terminals.
*	Large bandwidth - Communication bandwidth between any two terminals in a Meshee network can reach ~100Mbps.
*	Simulataneous use of Meshee network and cellular network - A terminal can use both Meshee networks and cellular network at the same time.
*	Multi-path transfering - Meshee networking and communications protocol can dynamically allocate bandwidth for multi-path transferring with load-balancing and fairness.
*	Resilient access - While the Internet vai 4G/WiFi is available,  terminals can use negeliable Internet traffic to obtain access information of Meshee networks, thereby improving accessing capability of Meshee networks significantly.
*	Communications format extension - Aiming different application requirements, Meshee supports fast extension of all sorts of multimedia communications format.
