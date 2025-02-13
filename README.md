<h1>GreyScript Pseudo-Interpreter (GrePsI)</h1>

GrePsI is a pseudo-interpreter for the game <a href="https://store.steampowered.com/app/605230/Grey_Hack/">Grey Hack</a>.  This shell environment mimics an interpreter for GreyScript by compiling then launching user code line-by-line & preserving variables between "runs" by shuttling them between the <code>global</code> and <code>get_custom_object</code> maps.

This tool is useful for testing, debugging & discovery.
