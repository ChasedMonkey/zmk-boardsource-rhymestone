<h1>Boardsource.xyz Rhymestone ZMK Configuration</h1>
<p><a href="https://www.boardsource.xyz/products/Rhymestone$0">Keyboard Kit</a>.</p>

This repo was made to configure the boardsource.xyz Rhymestone to work with ZMK if you chose to use a nice_nano_v2 or supermini controller.

This is not intended to be used with Blok or Elite-c controllers.

<h2>Optional Components</h2>
I have included everything that you should need if you chose to build with LED underglow or (an) OLED Screen(s).

LEDs are option and will quickly chew through battery life. But if you chose to use them like I did you only need to uncomment the LED lines in Rhymestone.conf And if you didn't include them you don't need to change anything.

The OLED screen(s) will need a little more setup. First uncomment the OLED related items in Rhymestone.conf

Once you have done that use the files in the OLED-enable folder to replace the files of the same names in the parent folder [Rhymestone]

You only need to replace the .dtsi and Rhymestone_left.overlay files if you are only using an OLED on the left piece. If you are using an oled on both sides you will need all 3 files.

The included 'Rhymestone_layout.json' in the config folder is only there to allow compatability with <p><a> href="https://nickcoutsos.github.io/keymap-editor/$0">this keymap editor</a>.</p>
You will also need to make a copy of Rhymestone.keymap and place it in the config folder for the keymap editor to work.
However I have configured this to work with ZMK studio, so you can also use that to edit the keymap if you desire.
