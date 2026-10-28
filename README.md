## Hi, I'm Brian 👋

I build things for my home, mostly ESP32 hardware with touchscreens and web dashboards that
make everyday equipment safer, smarter and nicer to use. Projects usually start with a
real problem around the house and end with firmware, a UI, Home Assistant integration and,
where it matters, a test suite.

### Featured projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/btkramer/ac-controller"><img src="images/ac-controller.png" alt="AC Controller"></a>
<h4><a href="https://github.com/btkramer/ac-controller">AC Controller</a></h4>
4" ESP32-S3 wall touchscreen for two mini-splits, driven by Home Assistant. LVGL 9.
</td>
<td width="50%" valign="top">
<a href="https://github.com/btkramer/well-pump-saver"><img src="images/well-pump-saver.png" alt="Well Pump Saver"></a>
<h4><a href="https://github.com/btkramer/well-pump-saver">Well Pump Saver</a></h4>
Motor protector and controller for a 2 HP well pump: Modbus power metering, flow sensing, dry-run and fault protection.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/btkramer/water-fill"><img src="images/water-fill.png" alt="WaterFill"></a>
<h4><a href="https://github.com/btkramer/water-fill">WaterFill</a></h4>
Automatic refill for CPAP and bed-cooler reservoirs. The control logic is fuzz-tested on a PC (4.1 M safety checks).
</td>
<td width="50%" valign="top">
<a href="https://github.com/btkramer/videsec"><img src="images/videsec.png" alt="Vide Sec"></a>
<h4><a href="https://github.com/btkramer/videsec">Vide Sec</a></h4>
A dry sous-vide cooker: a model-based cook engine with enforced pasteurization and an LVGL touchscreen UI.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/btkramer/aoostar-dashboard"><img src="images/aoostar-dashboard.png" alt="AOOSTAR Dashboard"></a>
<h4><a href="https://github.com/btkramer/aoostar-dashboard">AOOSTAR WTR MAX Dashboard</a></h4>
Custom front-panel LCD pages for a NAS: system, containers, storage and alerts that appear only when needed.
</td>
<td width="50%" valign="top">
<a href="https://github.com/btkramer/lilygo-rotary-knob"><img src="images/lilygo-rotary-knob.png" alt="PC Dash knob"></a>
<h4>PC Dash</h4>
A desktop knob and its ecosystem: USB-HID media control, now-playing, and a status ring for Claude Code sessions.<br><br>
• <a href="https://github.com/btkramer/lilygo-rotary-knob">lilygo-rotary-knob</a>: ESP32-S3 round-AMOLED firmware<br>
• <a href="https://github.com/btkramer/pc-dash-hub">pc-dash-hub</a>: FastAPI + Docker hub<br>
• <a href="https://github.com/btkramer/pc-dash-app">pc-dash-app</a>: .NET 8 Windows companion
</td>
</tr>
<tr>
<td colspan="2" valign="top">
<a href="https://github.com/btkramer/glyphstage"><img src="images/glyphstage.png" alt="Glyphstage"></a>
<h4><a href="https://github.com/btkramer/glyphstage">Glyphstage</a></h4>
Classic text adventures with every room drawn as a live 3D ASCII scene. Plays the original Zork I on its own Z-machine interpreter, with an auto-map and narrator.
</td>
</tr>
</table>

### What ties them together

- **Fail-safe first**: outputs off at boot, latched faults, watchdogs, and control logic that's
  unit- and fuzz-tested on a PC before it ever drives a relay
- **Interfaces people actually use**: designed in interactive mockups first, then built
  natively in LVGL or as a single-file web UI served by the device
- **Home Assistant everywhere**: MQTT or REST integration, OTA updates, and recovery on its
  own after a power cut

### Tools I use

ESP32 / ESP32-S3 · Arduino & PlatformIO · LVGL · C++17 · Python · FastAPI · .NET / C# ·
Docker · Home Assistant · MQTT · Modbus RTU · TrueNAS SCALE
