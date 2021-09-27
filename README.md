# Commands for FortBlox
So I have found some commands that could possibly be used for triggering events and more. so here they are<br><br>


== Basic ==<br>
Trigger Event: `Workspace.LiveEvents.<eventname>.Disabled = false`<br>
Destroy Object: `workspace.<object>:Destroy()`<br>
Changing Text Value: `game.ReplicatedStorage.Text.Value = "TextHere"` (Info: This does not work without enabling the ReplicatedStorage Value. Which I do not have)<br>
Kick Player Script: `for index, player in pairs(game.Players:GetPlayers()) do -- go thru every single player
	player:Kick("Thanks for watching the Operation Strike Event, We will now go under maintenance to fix the destruction as much as we can") -- kick the player
end -- end the for loop`
<br><br>
== Animation/Audio Clips ==<br>
-- Operation Strike Animation/Audio --<br>
CrystalCharge Audio: `game.Workspace.EventSounds.CrystalChargeUp:Play()`<br>
BeaconBeam Animation: `game.Workspace.BeaconBeam.Enabled = true`<br>
Alarm: `workspace.LiveEventSounds.Alarm_01:Play()`<br>
Laser Explosion: `game.Workspace.LaserExplosion1:Play()`<br>
Orb Explosion: `game.Workspace.LiveEventSounds.OrbExplosion:Play()`<br>
Orb Pushback: `game.Workspace.EventSounds.TheEndOrbPushBack:Play()`<br>
Pylon Rise: `game.Workspace.EventSounds.PylonRise:Play()`<br>
BeamShot #4: `game.Workspace.EventSounds.Beamshot4:Play()`<br>
Saturation Sounds: `game.Workspace.EventSounds.SaturationSound:Play()`<br>
Rift Sound: `game.Workspace.LiveEventSounds.RiftSound:Play()`<br>







