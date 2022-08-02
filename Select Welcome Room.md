# English
#### -Open Chrome Javascript Console (Ctrl+Shift+J on Windows/Linux or Cmd+Option+J on Mac)
#### -Paste this code and press Enter
```
function selectWelcomeRoom(a){fetch("https://"+window.location.host+"/api/newuser/room/select",{headers:{"content-type":"application/json"},body:'{"roomIndex":'+a+"}",method:"POST"}),window.location.reload()}document.body.innerHTML='<a class="hotel-button-native" onclick="window.location.reload();" style="margin-top: 10px;margin-left: 10px;max-width: fit-content;"><span class="hotel-button-native__text">Go back</span></a><br><center><h1>Select your welcome room:</h1><div style="display: flex;flex-flow: row wrap;justify-content: center;"><input onclick="selectWelcomeRoom(1)" type="image" src="https://images.habbo.com/c_images/nux/nux_room_10_round.png" style="border: groove;padding: 10px;margin: 10px"/><input onclick="selectWelcomeRoom(2)" type="image" src="https://images.habbo.com/c_images/nux/nux_room_11_round.png" style="border: groove;padding: 10px;margin: 10px"/><input onclick="selectWelcomeRoom(3)" type="image" src="https://images.habbo.com/c_images/nux/nux_room_12_round.png" style="border: groove;padding: 10px;margin: 10px"/></div>'
```
#### -Now you can see the welcome room selection screen
#
# Español
#### Abre la Consola Javascript de Chrome (Ctrl+Shift+J en Windows/Linux o Cmd+Option+J en Mac)
#### Pega el siguiente codigo y presiona Enter:
```
function selectWelcomeRoom(a){fetch("https://"+window.location.host+"/api/newuser/room/select",{headers:{"content-type":"application/json"},body:'{"roomIndex":'+a+"}",method:"POST"}),window.location.reload()}document.body.innerHTML='<a class="hotel-button-native" onclick="window.location.reload();" style="margin-top: 10px;margin-left: 10px;max-width: fit-content;"><span class="hotel-button-native__text">Go back</span></a><br><center><h1>Select your welcome room:</h1><div style="display: flex;flex-flow: row wrap;justify-content: center;"><input onclick="selectWelcomeRoom(1)" type="image" src="https://images.habbo.com/c_images/nux/nux_room_10_round.png" style="border: groove;padding: 10px;margin: 10px"/><input onclick="selectWelcomeRoom(2)" type="image" src="https://images.habbo.com/c_images/nux/nux_room_11_round.png" style="border: groove;padding: 10px;margin: 10px"/><input onclick="selectWelcomeRoom(3)" type="image" src="https://images.habbo.com/c_images/nux/nux_room_12_round.png" style="border: groove;padding: 10px;margin: 10px"/></div>'
```
#### Ahora podras ver la pantalla de seleccion de la sala de bienvenida
