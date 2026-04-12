Looking for the download page? ⬇️
https://github.com/LilithRainbows/HabboAirPlus/releases/latest

*********************************************************************
To view and edit project's source code you need to download JPEXS:
https://github.com/jindrapetrik/jpexs-decompiler/releases/latest
*********************************************************************

Client version: WIN63-202603091410-618570407
AIR SWF version: 51
JPEXS version: 22.0.2

Enabled commands:
:backlight [0-255] (set room backlight value with forced mode)
:roomlight [0-255] (set room light value with forced mode)
:bgcolor [HueNumber] [SaturationNumber] [LightnessNumber] (change room background color with forced mode)
:fps Number (change current fps value with forced mode)
:unlockfps (unlock/lock animations fps with forced mode)
:respect (give respects to clicked user) (USE AT OWN RISK)
:safetybook (show hotel safety book)
:habboway (show habbo way info)
:handitem [ItemId] (change current user handitem) (IN SERVER-SIDE CASES USE AT OWN RISK)
:calendar (open calendar) (USE AT OWN RISK)
:linkevent [Link] (open a linkevent) (IN SERVER-SIDE CASES USE AT OWN RISK)
:lightsaber (toggle lightsaber fx)
:autoclick (toggle autoclick mode)
:autoclickdelay (change autoclick delay)
:resetvars (reset saved client variables)
:infostand (toggle furni/user infostand visibility)
:chatmute (mute/unmute room chat with forced mode and without affecting chat history)
:chatsize [12-40] (change chat font size with forced mode)
:seasonal (toggle client seasonal colors)
:color [HexColor/classic/pink] (change client title bar color)
:barcolor [HexColor/classic/pink] (change client bottom bar color)
:winblend [0.0 to 1.0] (change client window blend value)
:barblend [0.0 to 1.0] (change client bottom bar blend value)
:barstyle (toggle client bottom bar alternative style)
:playing (toggle click-through with forced mode)
:fx [FxId] (change current user fx with forced mode) (IN SERVER-SIDE CASES USE AT OWN RISK)
:dance [0-4] (change current dance style)
:clone [optional:Sex(M or F)] (clone clicked user look)
:afk (toggle anti afk with forced mode)
:ping (get latest ping value) (USE AT OWN RISK)
:pingsay (publicly say latest ping value) (USE AT OWN RISK)
:pingbeforetext (change text before ping value)
:pingaftertext (change text after ping value)
:pingbubble [optional:auto] (change pingsay bubble to current selected chat bubble style)
:typing (toggle chat typing indicator) (USE AT OWN RISK)
:rotate (toggle room rotate effect)
:adblock (toggle mpu ad blocker) (IN SERVER-SIDE CASES USE AT OWN RISK)
:figure [FigureCode] [optional:FigureSex(M or F)] (change avatar figure)
:acceptquest [QuestId] (manually accept quest by id)
:say [Something] (say something, even commands)
:shout [Something] (shout something, even commands)
:whisper [Something] (whisper something to clicked user, even commands)
:give or :pass (give handitem to clicked user/pet) (USE AT OWN RISK ON PETS)
:hkset [optional:ChatInput] (set a new chat input hotkey)
:hkmode (toggle hotkey press mode)
:hkshow (show saved hotkeys)
:hkclear (clear chat input hotkeys)
:f1 to :f12 [optional:ChatInput] (quickly set new chat input hotkey with function keys)
:commands (show airplus commands list)
:cmdcolor (toggle command input color hint + tab autocompletion)
:chatcolor (toggle users custom chat text color)
:about or :version (show client version info)
:dc (toggle use furnitures on single click)
:nodc (toggle furniture double click capability)
:zoomgestures (toggle zoom gestures capability)
:flood [optional:ChatInput]  (toggle chat input flood)
:flooddelay (change chat input flood delay)
:tradeblock (toggle trade block)
:walkblock (toggle walk block)
:chatalarm [TriggerText] (toggle chat sound alarm)
:turnblock (toggle avatar turn/lookto block)
:wcublock (toggle wiredclickuser block)
:zoomf [Value] (toggle fractional room zoom with forced mode)
:clickuser [UserTempId/LatestClickedUser] (click the selected user)
:clickfurni [FurnitureId/LatestClickedFurniture] (click the selected furniture)
:usefurni [FurnitureId/LatestClickedFurniture] (use the selected furniture)
:movetofurni [FurnitureId/LatestClickedFurniture] (move to the selected furniture)
:aprilfools (request april fools 2025 badges) (USE AT OWN RISK)
:crash (generate a critical error)
:showerrors (show/hide critical client errors)
:friendhl (toggle friend name entrance highlight)
:fon [0-2] (0=disabled/1=enabled for all/2=enabled for relationships) (show a notification when a friend goes online)
:shift (toggle shift key to walk block)
:ctrl (toggle ctrl key to use furnitures on single click)
:hideignoredbubble (toggle hide ignored users bubble)
:spawn [FurniName] [optional:FurniState] (spawn requested furni at current user position/direction) (IN SERVER-SIDE CASES USE AT OWN RISK)
:laugh (laugh expression, hc only)
:furnitech (open sandbox self donate window) (client side only)
:mutepets (toggle pets mute with forced mode)
:mutebots (toggle bots mute with forced mode)
:mutecmd (toggle commands chat hints)
:clearchat (clear room chat)
:clearhist (clear chat history)
:caution (show/hide moderation caution alerts)
:hidefigures (hide all users with the current selected figure)
:hidepoints [MaxPoints] (hide all users with less or equal activity points)

Enabled features:
-Auto maximize client window at startup
-Chooser, furni and bcfloor commands always available
-Fixed https protocol
-Forced sit and stand command
-Fixed connection.login.code.prompt text
-Fixed photo thumbnails visualization
-Improved playing mode (while active the cursor will be an arrow and look to users will be blocked)
-Customized login screen background
-Now commands variables are saved
-Fixed avatar menu arrow icons
-Improved catalog badges visualization
-Fixed decorated gift box icon visualization (MAY HAVE ERRORS)
-Updated defaut avatar editor figures
-Restored original clickRoomObject functionality (to allow alt, ctrl or shift with single click on room object)
-Allow local load of furni swf files (needs to be located inside local_include folder)
-Max chat input for commands increased to 200 characters (also typing indicator will be temporarily disabled)
-Removed mannequins gender/hc limitations (in addition to avoiding crashes due to bugged mannequins)
-Autofocus sso login screen inputfield
-Fixed black screen after opening gift dialogs and improved untrusted gift message localization
-Now the default language of the login screen depends on the system language
-Fixed bc catalog window title
-Fixed dynamic get of isRoomOwner function
-Added visual color indicator to know if a command is valid
-Disabled chat input flood lock to allow using commands even with flood
-Disable chat text paste limitation
-Disabled PollReject to avoid poll cancelation (but they remain hidden during current game session)
-Improved seasonal decoration
-Fix login token validation
-Fixed room rendering at very large resolutions
-Fixed black color inconsistency in the top background of rooms on HDR/OLED displays
-Fixed random unresponsive left part of the screen (where the chat history is located) (beta fix)
-Fixed a bug that prevent users context menus visibility when iterating between rooms (beta fix)
-Fixed current room info collapse
-Removed wired save confirmation message
-Improved friend name highlight system
-Now zoom level 1 centers camera position
-Avoid remote errors logs and force full local errors logs
-Improved memenu toolbar icon
