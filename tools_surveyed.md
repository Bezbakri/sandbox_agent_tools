Agno tools (https://github.com/agno-agi/agno/tree/main/libs/agno/agno/tools):
	CalComTools: read API key, visit cal.com
	Crawl4ai: arg urls
	Browserbase: arg urls, paths to save files
	adanos: access urls
	advisor: basic
	csvtools: duckdb connection, access csv files
	docker: access to docker
	email: send emails
	localfilesystem: read and write files
	opencv: access to filesystem, access to camera (VERY DANGEROUS)
	postgres: access to postgres db
	webbrowser: access to web browser, ability to open a page
	CodeMode : execute Python/code, access kernel state, read/write execution snapshots
	ToolBridge : connect to and invoke other tools
	SnapshotManager : read/write code execution session state and variables to filesystem
	KernelSession : execute code in a Jupyter kernel, manage kernel processes
	LoopRunner : execute/manage asynchronous code execution loops
	FileTools : read, write, replace, delete, list, and search files
	FileGenerationTools : create and write JSON, CSV, PDF, text, HTML, DOCX, and code files
	FinanceTools : access financial market data through configured providers
	YFinance : access Yahoo Finance market data
	FinancialDatasets : access Financial Datasets API
	FinanceProvider : access provider-backed financial data such as quotes, price history, financials, news, insider trades, earnings, and SEC filings
	GoogleAuth : access Google OAuth credentials/tokens and authenticate Google services
	GoogleBigQueryTools : access BigQuery datasets/tables and execute SQL queries
	GmailTools : read, search, create, send, modify, archive, label, and delete Gmail messages
	GoogleCalendarTools : read, create, update, delete, move, and respond to Google Calendar events
	GoogleDriveTools : list, search, read, upload, and download Google Drive files
	GoogleSlidesTools : create, read, modify, move, duplicate, and delete Google Slides presentations/slides; insert media
	GoogleMapTools : access Google Maps/Places APIs; search places, geocode addresses, directions, distance, elevation, timezone
	GoogleSheetsTools : read, create, update, and duplicate Google Sheets
	KnowledgeTools : search/query the configured knowledge base and analyze retrieved knowledge
	KnowledgeManagementTools : ingest URLs, filesystem paths, and text into the knowledge base; list, inspect, and remove knowledge content
	MCPTools : connect to and invoke tools exposed by remote/local MCP servers

https://github.com/virgiliojr94/book-to-skill/tree/master/tools
	 DiscoverTax: Find file path, access files
	 scan_generated_skill: Look at available files, access files
	 validate_skill: same as above
https://github.com/NousResearch/hermes-agent/tree/main/tools
	web_search	Public web search only	 
	web_extract	Read explicitly requested URLs/pages	 
	x_search	Public X search only	 
	read_file	Read only explicitly scoped files/directories	 
	search_files	Search only explicitly scoped workspace	 
	patch	Modify only explicitly scoped files; require approval	 
	write_file	Deny by default; enable only for requested files	 
	terminal	Sandboxed command execution only	 
	process	Manage only processes created by this agent/session	 
	browser_navigate	Navigate to requested URLs/domains	 
	browser_snapshot	Read current browser page	 
	browser_click	Click only within approved browser session	 
	browser_type	Require confirmation before credentials/submission	 
	browser_press	Same boundary as browser interaction	 
	browser_scroll	Page-local navigation	 
	browser_back	Browser-session-local navigation	 
	browser_get_images	Read image URLs/metadata from current page	 
	browser_vision	Screenshot current browser page	 
	browser_console	Read current page console	 
	browser_cdp	Deny unless explicitly needed	 
	browser_dialog	Deny unless explicitly needed	 
	vision_analyze	Analyze user-provided/explicitly selected images	 
	video_analyze	Analyze explicitly supplied video	 
	image_generate	Generate/edit media; external provider access	 
	video_generate	Generate video through configured provider	 
	xai_video_edit	Edit supplied media	 
	xai_video_extend	Extend supplied media	 
	text_to_speech	Convert supplied text to speech	 
	execute_code	Deny by default; it can invoke Hermes tools programmatically	 
	delegate_task	Spawn only narrowly scoped subagents	 
	clarify	Ask user questions	 
	todo	Session-local task state	 
	memory	Deny or require explicit approval for writes	 
	session_search	Read only sessions explicitly in scope	 
	skills_list	List skills	 
	skill_view	Read selected skill	 
	skill_manage	Deny by default; skill creation/update/delete	 
	cronjob	Deny by default; scheduling persists beyond session	 
	computer_use	Deny by default; desktop-wide interaction	 
	project_list	Read project metadata	 
	project_switch	Switch workspace	 
	project_create	Create workspace	 
	ha_list_entities	Read Home Assistant entity inventory	 
	ha_get_state	Read state of explicitly scoped entities	 
	ha_list_services	Read available HA actions	 
	ha_call_service	Only explicitly authorized entity/service	 
	spotify_search	Search Spotify	 
	spotify_albums	Read album information	 
	spotify_devices	Read playback-device information	 
	spotify_library	Read library	 
	spotify_playback	Change playback only	 
	spotify_queue	Modify playback queue	 
	spotify_playlists	Read; writes require approval	 
	discord	Read/send Discord messages within approved server/channel	 
	discord_admin	Deny by default	 
	feishu_doc_read	Read explicitly selected documents	 
	feishu_drive_list_comments	Read comments on selected file	 
	feishu_drive_list_comment_replies	Read selected comment thread	 
	feishu_drive_add_comment	Write comment to selected document	 
	feishu_drive_reply_comment	Reply to selected comment	 
	yb_query_group_info	Read group metadata	 
	yb_query_group_members	Read group membership	 
	yb_search_sticker	Search stickers	 
	yb_send_dm	Send DM to explicitly approved recipient	 
	yb_send_sticker	Send to explicitly approved recipient/group	 
	kanban_show	Read assigned task	 
	kanban_list	Read board/task metadata	 
	kanban_complete	Mutate current task state	 
	kanban_block	Mutate current task state	 
	kanban_heartbeat	Update current task status	 
	kanban_comment	Write to task thread	 
	kanban_create	Create child tasks	 
	kanban_link	Modify task dependencies	 
	kanban_unblock	Change task state	 
	kanban_request_review	Change workflow state	 
	kanban_request_changes	Change workflow state	 
	kanban_attach	Upload file into board	 
	kanban_attach_url	Server-side URL download + upload	 
	kanban_attachments	Read attachment metadata/path	 
https://github.com/Graphify-Labs/graphify/blob/v8/tools/skillgen/gen.py
	  Read, write files in folder, run python and git

https://github.com/browser-use/browser-use/tree/main
	 Full access to browser
https://github.com/modelcontextprotocol/servers-archived/blob/main/src/sqlite/src/mcp_server_sqlite/server.py
	 read/write access to db
https://github.com/ryoungj/ToolEmu/blob/main/toolemu/tools/
	Real:
		RealTerminalExecute: filesystem access
		RealPythonInterpreter: filesystem access
		RealWikipedia: access to wikipedia
		RealHuman: Read and write stdin/stdout
https://github.com/2slides/mcp-2slides
	slides_generate: 2slides API key, outbound HTTPS to 2slides.com, create PowerPoint presentations, consume account credits
	themes_search: 2slides API key, outbound HTTPS to 2slides.com, read/search available themes
	jobs_get: 2slides API key, outbound HTTPS to 2slides.com, read job status and retrieve generated-file download URLs
	slides_create_like_this: 2slides API key, outbound HTTPS to 2slides.com, submit presentation content + arbitrary reference image URL, generate image-based slides, consume account credits
	slides_create_pdf_slides: 2slides API key, outbound HTTPS to 2slides.com, submit presentation content/design instructions, generate image-based slides, consume account credits
	slides_generate_narration: 2slides API key, outbound HTTPS to 2slides.com, submit speaker/narration parameters for an existing job, generate AI voice narration, consume account credits
	slides_download_slides_pages_voices: 2slides API key, outbound HTTPS to 2slides.com, retrieve generated ZIP download URL containing slide images, audio files, and transcript
https://github.com/urnetwork/docs/blob/main/mcp/SKILL.md
	URnetwork MCP: OAuth/JWT credential, outbound HTTPS to mcp.bringyour.com, create/manage network proxy clients
	providerLocations: URnetwork account auth, outbound HTTPS to mcp.bringyour.com, read provider/location metadata
	fetch: URnetwork account auth, outbound HTTPS to mcp.bringyour.com, fetch URLs through a selected URnetwork egress location, access to returned cookies/continuation/signed_proxy_id state
https://github.com/OctagonAI/octagon-deep-research-mcp
	octagon-deep-research-agent: Octagon API key, requests to Octagon