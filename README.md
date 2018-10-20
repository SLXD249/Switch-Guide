Nintendo Homebrew Channel 2.0 Master Guide<br/>
Page 1 - Introduction<br/>
Ever since the Wii, Nintendo has been one of the most easily hackable companies to date. In fact, it seems that over time, once the proper tools are available, it's become easier and easier for the average gamer to modify their own systems. But for the most part, the methods and tools needed to do so are scattered all over the internet and are only accessible by those who know where to look. Also, some people also don't know what types of tools are the most beneficial. But what we will attempt to do is centralize the basic Nintendo hacking system, which will literally spell out in plain English what you need to perform a successful hack without all the technical mumbo-jumbo that most sites tend to throw in. We will make it so that virtually any noob can hack their systems from scratch with little to no beginning knowledge of all the fine details. This guide was made on an entirely volunteer service from people who care about hacking Nintendo and are willing to share the knowledge with others.<br/>
<br/>
Part 2 - Hacking FAQ<br/>
Question: What is RCM Mode?<br/>
Is it safe to use homebrew or will I get banned?<br/>
The Switch comes with a lot of telemetry. As long as the Switch is connected to the internet, Nintendo gets a report about a lot of different actions and states and has the option to log or act on them. Even if the Switch is offline and connects to the internet at a later point, Nintendo still recieves information about what happened while the Switch was disconnected.<br/>
<br/>
To disable some of this telemetry it is adviced to disable the sending of error reports in the System Settings of the Switch. Additionally if you live in the EU you can set the "do not share" option on https://accounts.nintendo.com/setting to prevent your Switch from sending a lot of telemetry.<br/>
<br/> 
Nintendo still recieves a lot of information, even with those options disabled. We also cannot know if Nintendo decides to look for something in the logs and ban people in retrospect. They have also shown to expand their telemetry options with every other firmware update.<br/>
<br/> 
Currently all bans have been for very obvious and intrusive actions, specifically:<br/>
 - Developers using their unique Switch data to poke and reverse-engineer Nintendos Server responses<br/>
 - People pirating games and using them online<br/>
 - People changing their profile pictures to custom pictures (which is not possible without pirating the Nintendo SDK)<br/>
 - People using savegame editors to unlock content that is not available yet and using it online (Splatoon 2)<br/>
 - People cheating online in general (Modifying Cart stats in MK8)<br/>
<br/> 
This however does not mean that Nintendo won't decide to ban people for harmless homebrew in the future. If you are scared to get banned then don't use homebrew for now. Once Atmosphere CFW releases we will be able to create a dual-boot (emunand) solution, that allows us to have a clean, online firmware and a seperate offline firmware for homebrew related things. Unbanning on the Switch will be a lot harder, if not impossible.<br/>
<br/>
What is a "jig"?<br/>
A jig is a small piece of metal that is used to bridge the gaps between two of the "pins" in the right Joy-Con port in order to hard-wire RCM Mode. These items usually differ from a modified paper clip or a piece of aluminum foil or a custom-made 3d-printed item that fits in the port to trip the pins. However, one must be very careful what pins you trip, because not only are they very small and difficult to see, but if you trip "pin number 7", you will automatically brick your switch. Therefore, it is highly recommended that you buy a prefabricated one from Amazon for the average price of $3-$7<br/>
<br/>
What is a payload?<br/>
Payload senders (or payload injectors, or code loaders), are programs or devices used to transfer a small binary file (the payload) to the Nintendo Switch while being in Recovery mode (RCM), which allows early custom program's execution at console boot before the Switch official Operating System (Horizon OS) is loaded.<br/>
<br/>
What is RCM Mode?<br/>
The Nintendo Switch RCM Mode is used for hacking purposes, specifically for launching into Custom Firmware. Booting into RCM is done based off of a hardware mistake in the Nintendo Switch, and the CFW (custom firmware) is based off of a glitch in recovery mode (RCM).<br/>
<br/>
Part 4 - Getting Started<br/>
In order to effectively hack your switch on virtually any currently available firmware, you need the following items and software<br/>
<br/>
1. An RCM Jig - This is the most important part. Without the classic jig, you can't force the RCM mode that is the core of Switch hacking. Some people can get creative by bending a paper clip or tinfoil, but for noobs, this is not recommended since the small "pins" in the right Joy-Con slot are incredibly difficult to see, and if you accidentally trip what's known as "Pin 7", you will instantly brick your switch. Some people luck out by being able to 3d print them, but for everyone else, they go for dirt cheap on Amazon for between $3 and $7.<br/>
<br/>
2. USB-C Cord or Portable payload Injector - Just as important as the jig, you can't activate Custom Firmware without performing what's known as a "payload injection", which can only be applied from an outside data source.
