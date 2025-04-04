Client version: WIN63-202503281213-878071447 (ported and spoofed as WIN63-202504011439-511701537)
AIR SWF version: 51 (spoofed as 50 for compatibility reasons)
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
:givegem [Amount] (give gems to clicked user) (USE AT OWN RISK)
:lightsaber (toggle lightsaber fx)
:furnimark (toggle furnimark mode) (CURRENTLY NOT WORKING)
:autoclick (toggle autoclick mode)
:autoclickdelay (change autoclick delay)
:devwar (test all available clothes with forced mode) (optional: figure can be loaded from clicked user) (IN SERVER-SIDE CASES USE AT OWN RISK)
:stopdevwar (stop devwar command and recover your real look)
:resetvars (reset saved client variables)
:infostand (toggle furni/user infostand visibility)
:chatmute (mute/unmute room chat with forced mode and without affecting chat history)
:chatsize [12-40] (change chat font size with forced mode)
:showbubbles (show all chat bubbles styles)
:color [HexColor/classic/pink] (change client title bar color)
:barcolor [HexColor/classic/pink] (change client bottom bar color)
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
:showids (toggle objects ids viewer)
:typing (toggle chat typing indicator) (USE AT OWN RISK)
:spoofbubbles [optional:own] (spoof chat bubbles to current selected chat bubble style)
:rotate (toggle room rotate effect)
:adblock (toggle mpu ad blocker) (IN SERVER-SIDE CASES USE AT OWN RISK)
:figure [FigureCode] [optional:FigureSex(M or F)] (change avatar figure)
:showquestsids (toggle quests ids)
:acceptquest [QuestId] (manually accept quest by id)
:say [Something] (say something, even commands)
:shout [Something] (shout something, even commands)
:whisper [Something] (whisper something to clicked user, even commands)
:give or :pass (give handitem to clicked user/pet) (USE AT OWN RISK ON PETS)
:hkset [optional:ChatInput] (set a new chat input hotkey)
:hkclear (clear chat input hotkeys)
:f1 to :f12 [optional:ChatInput] (quickly set new chat input hotkey with function keys)
:commands (show airplus commands list)
:cmdcolor (toggle command input color hint + tab autocompletion)
:chatcolor (toggle users custom chat text color)
:about or :version (show client version info)
:nodc (toggle furniture double click capability)
:zoomgestures (toggle zoom gestures capability)
:flood [optional:ChatInput]  (toggle chat input flood)
:flooddelay (change chat input flood delay)
:tradeblock (toggle trade block)
:walkblock (toggle walk block)
:chatalarm [TriggerText] (toggle chat sound alarm)
:turnblock (toggle avatar turn/lookto block)
:wcublock (toggle wiredclickuser block)
:zoomf [Value] (toggle fractional room zoom)
:fpsboost [auto/always/never] (toggle low fps boost) (always not recommended unless you have very low fps)
:usefurni [FurnitureId/LatestClickedFurniture] (use the selected furniture)
:movetofurni [FurnitureId/LatestClickedFurniture] (move to the selected furniture)
:aprilfools (open april fools mod tool) (USE AT OWN RISK)

Enabled features:
-Auto maximize client window at startup
-Chooser, furni and bcfloor commands are now available for all users
-Fixed https protocol
-Forced sit and stand command
-Fixed connection.login.code.prompt text
-Fixed photo thumbnails visualization
-Fixed closed profiles visualization
-Improved playing mode (while active the cursor will be an arrow and look to users will be blocked)
-Disabled furniture selection lock
-Now users relationships will remain invisible until they load
-Customized login screen background
-Removed EncryptedLocalStorage
-Now commands variables are saved
-Allow voting for both options on community goals 
-Fixed avatar menu arrow icons
-Improved catalog badges visualization
-Fixed decorated gift box icon visualization (MAY HAVE ERRORS)
-Updated defaut avatar editor figures
-Restored original clickRoomObject functionality (to allow alt, ctrl or shift with single click on room object)
-Forced selected chat bubble style save
-Allow local load of furni swf files (needs to be located inside local_include folder)
-Max chat input for commands increased to 200 characters (also typing indicator will be temporarily disabled)
-Removed mannequins gender/hc limitations (in addition to avoiding crashes due to bugged mannequins)
-Autofocus sso login screen inputfield
-Fixed gifts calendar icon and title
-Fixed black screen after opening gift dialogs and improved untrusted gift message localization
-Now the default language of the login screen depends on the system language
-Fixed bc catalog window title
-Fixed dynamic get of isRoomOwner function
-Added visual color indicator to know if a command is valid
-Disabled chat input flood lock to allow using commands even with flood
-Disabled PollReject to avoid poll cancelation
-Improved xmas decoration
-Fix login token validation
-Fixed room rendering at very large resolutions
-Fixed black color inconsistency in the top background of rooms on HDR/OLED displays
