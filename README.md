Stop Motion Helper
==================
Stop Motion Helper is a tool for Garry's Mod designed to make stop motion animation easier and more manageable.
It can also be used for recorded animation, but it is mainly designed around stop motion.

This repo is just for my small mods for it which are listed below.


lua\smh\client\state.lua

    SMH.State = {
      PlaybackRate = 60,
      PlaybackLength = 700,
  }


lua\smh\client\derma\save.lua
lua\smh\client\derma\load.lua

    self:SetSize(500, 1000)
    self:SetPos(ScrW() - self:GetWide(), ScrH() - self:GetTall())
	

lua\smh\client\derma\frame_panel.lua

    self.Zoom = 400

lua\smh\client\renderer.lua

    RunConsoleCommand(command, "SMH")
