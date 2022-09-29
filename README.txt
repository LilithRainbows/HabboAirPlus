Client version: WIN63-202206291351-193092611
JPEXS version: 15.0.0

:give (give handitem to clicked user/pet) (USE AT OWN RISK ON PETS)
:fon Number (0=disabled/1=enabled for all/2=enabled for relationships) (show a notification when a friend goes online)
:bcolor HueNumber SaturationNumber LightnessNumber (change room background color with forced mode)
:chatsize (12-40) (change chat font size)
:autoclick (toggle autoclick button)
:showids (toggle objects ids viewer)
:ping (get latest ping value)
:unitybadges (get unity exclusive badges) (USE AT OWN RISK)
:snowclothing (blue or red) (secondary color value) (set snowstorm clothing) (IN SERVER-SIDE CASES USE AT OWN RISK)
:fps Number (change current fps - default value is 24)
:backlight (0-255) (set room backlight value)
:roomlight (0-255) (set whole room light value)
:forcedmute Username (force a 72-hour user mute) (USE AT OWN RISK)
:afk (toggle anti afk mode)
:respect (give respects to clicked user) (USE AT OWN RISK)
:givegem Amount (give gems to clicked user) (USE AT OWN RISK)
:clone (clone clicked user look)
:dance (0-4) (change current dance style)
:playing (toggle click-through with forced mode)
:fx FxId (change current user fx with forced mode) (IN SERVER-SIDE CASES USE AT OWN RISK)
:handitem ItemId (change current user handitem) (IN SERVER-SIDE CASES USE AT OWN RISK)
:devwar (test all available clothes) (optional: figure can be loaded from clicked user) (IN SERVER-SIDE CASES USE AT OWN RISK)
:calendar (open calendar) (USE AT OWN RISK)
:linkevent Link (open a linkevent) (IN SERVER-SIDE CASES USE AT OWN RISK)

-Visit, roomid, chooser, furni and bcfloor commands are now available for all users
-Fixed https protocol
-Disabled clipboard paste lock
-Disabled external MPUs images (only images.habbo.com is allowed)
-Give star gems from user profile instead of user context menu
-Fixed user profile level text
-Fixed furni chooser items width
-Disabled furniture selection lock
-AutoClick button added to furni menu
-Fixed sound fxs playback
-Disabled mannequin hc validator (this also avoid crashes)
-Allow voting for both options on community goals
-Fixed campaign calendar icon
-Removed wired save confirmation message
-Fixed closed profiles visualization
-Fixed decorated gift box icon visualization
-Fixed photo thumbnails visualization
-Fixed avatar menu arrow icons
-Improved mute actions
-Forced sit and stand command
-Fixed connection.login.code.prompt text
-Added friend remove button to messenger
-Added buttons to enable/disable/clean cache to login screen
-Fixed messenger settings button
-Added warning about scam sites to messenger
-Fixed login screen background images
-Auto maximize client window at startup
-Added safetybook and habboway commands
-Fixed camera movement bug (unconfirmed)
-Now the default language of the login screen depends on the system language
-Improved catalog badges visualization
-Now a notification is displayed by default when a friend added to relationship goes online
-Improved playing mode (while active the cursor will only be an arrow and outgoing messages will be blocked when clicking an user)
-Now users relationships will remain invisible until they load
