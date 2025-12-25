# Matter Brand Experience (MBX)
## Your Brand. Every Platform. Zero Apps.

### A Presentation to the Connectivity Standards Alliance

**Duration:** 20 minutes

<div style="page-break-after: always;"></div>

# Matter Brand Experience

## Your Brand. Every Platform. Zero Apps.

**For:** Connectivity Standards Alliance

![](matter_logo.png)

**SPEAKER NOTES:**

Opening energy: Start strong. This is about transforming Matter from a protocol standard into a complete user experience standard.

Key message: "Today I'm going to show you how we can fulfill Matter's original promise—and create massive value for vendors, platforms, and users—with one elegant addition to the ecosystem."

*Timing: 30 seconds*

<div style="page-break-after: always;"></div>

# The Smart Home Today

![](frustration.png)

**SPEAKER NOTES:**

Let this image speak. Pause and let them look.

"This is the reality for smart home users today. 6+ apps. Notification chaos. Battery drain. And this person has a SIMPLE smart home."

"Every device vendor says 'download our app for the full experience.' So users do. Again and again."

Stats to mention:
- Average smart home user has five or six device apps installed
- 67% of users cite "too many apps" as their #1 frustration
- Each app requires account creation, learning new UI, managing updates

*Timing: 1 minute*

<div style="page-break-after: always;"></div>

# Matter's Broken Promise

> "Buy any Matter device. Use any app. It just works."

**The Reality:**

| Platform App Shows | Full Features Require |
|-------------------|----------------------|
| On/Off | Vendor app |
| Brightness | Vendor app |
| Basic temperature | Vendor app |
| Lock/Unlock | Vendor app |

**"For schedules, scenes, and settings... download our app."**

**SPEAKER NOTES:**

"Matter delivered on the protocol promise. Discovery, commissioning, basic control—all interoperable. That's a huge achievement."

"But Matter has NOTHING to say about user interfaces. So what happens?"

"A Philips Hue bulb in Apple Home? You get on/off and brightness. That's it. Want scenes? Hue Sync? Entertainment mode? Download the Hue app."

"An Ecobee thermostat? Basic temperature in Google Home. Want schedules, sensor data, energy reports? Download the Ecobee app."

"We standardized the protocol but left the experience fragmented."

*Timing: 1.5 minutes*

<div style="page-break-after: always;"></div>

# The Solution: Matter Brand Experience

![](unification.png)

**SPEAKER NOTES:**

"What if there was ONE app—whichever app the user prefers—that gave them FULL control of EVERY device, with FULL vendor branding?"

Point to the image:
- "One Home app icon. That's it."
- "Every device—lights, thermostat, locks, sensors—fully controllable"
- "Users choose their preferred platform. They're done."

"This is Matter Brand Experience. MBX."

*Timing: 1 minute*

<div style="page-break-after: always;"></div>

# See It In Action

![](MDUI_example_screens.png)

**SPEAKER NOTES:**

Walk through each screen LEFT TO RIGHT:

1. "STANDARD - This is the CSA-provided module. Works for any color light. No branding. Full functionality. This is what you get if a vendor does nothing."

2. "BRANDED - Philips adds their Hue logo and a 'Hue Scenes' button. Same underlying controls, but now it's THEIR experience. Their brand is in Apple Home, Google Home, Amazon Alexa."

3. "EXTENDED - A different vendor, Lowpan, adds a schedule indicator. Users see 'Sunset → Sunrise' right on the main screen."

4. "EXTENDED UI - Tap that schedule indicator, a native bottom sheet opens with full scheduling controls."

"All four screens render with NATIVE iOS components. On Android, they'd use native Material Design. The platform controls the look and feel. The vendor controls the CONTENT."

*Timing: 2 minutes*

<div style="page-break-after: always;"></div>

# Your Brand. Every Platform.

![](branded.png)

**SPEAKER NOTES:**

"Look at this. Apple Home. Google Home. Amazon Alexa. THREE different platforms."

"Same Philips branding. Same 'hue' logo. Same PHILIPS in the control. Identical experience."

"For vendors, this is the dream: your brand presence in EVERY major smart home platform, without building and maintaining THREE separate apps."

"For platforms, the ecosystem gets richer without any work on their part."

"For users, they don't care which platform they chose—they get the full Philips Hue experience regardless."

*Timing: 1.5 minutes*

<div style="page-break-after: always;"></div>

# How Easy Is It?

![](workflow.png)

**SPEAKER NOTES:**

"Here's what vendors actually do:"

1. "FORK - Download the CSA standard module for your device type. It's Lua code—simple, readable, about 100 lines for a typical device."

2. "BRAND - Add your logo. Add your colors. Add your special features. The standard controls are already there—you're EXTENDING, not rebuilding."

3. "SUBMIT - Upload to the CSA registry. Automated testing, certification, signing. Same process vendors already know from Matter certification."

4. "DONE - Your branded UI is live on every platform. No app store reviews. No platform-specific builds. Just... done."

"A competent developer can do this in a DAY. Not months. Not weeks. A day."

*Timing: 1.5 minutes*

<div style="page-break-after: always;"></div>

# Who Wins: Device Vendors

## Write Once. Brand Everywhere.

| Before MBX | With MBX |
|-----------|---------|
| Build iOS app | Write ONE Lua module |
| Build Android app | (~100 lines of code) |
| Maintain both forever | Submit once |
| App store fees & reviews | Live on ALL platforms |
| Support burden | CSA handles distribution |

**Your brand in Apple Home, Google Home, Amazon Alexa—without building a single app.**

**SPEAKER NOTES:**

"For device vendors, this is transformational."

"Today, if you want your brand and full features accessible to users, you build apps. iOS app: Swift, SwiftUI, yearly iOS updates, App Store review. Android app: Kotlin, Compose, device fragmentation, Play Store review."

"With MBX, you write approximately 100 lines of Lua. You fork the standard module, add your logo, add your features. Submit it. Done."

"Your brand appears in Apple Home, Google Home, Amazon Alexa. No app maintenance. No app store fees. No review process beyond CSA certification."

"Small vendors especially benefit. A two-person startup can have the same platform presence as Philips."

*Timing: 1.5 minutes*

<div style="page-break-after: always;"></div>

# Who Wins: Platform Vendors

![](platform_savings.png)

**SPEAKER NOTES:**

"Now let's talk about why Apple, Google, and Amazon should LOVE this."

Point to LEFT side:
"WITHOUT MBX, platforms must build custom UI for every device type. 50+ device types, times 3 platforms, equals 150+ implementations. Ongoing maintenance forever. Every time CSA adds a new device type, every platform team scrambles."

Point to RIGHT side:
"WITH MBX, platforms build TWO things: a Lua runtime and a UI renderer. That's it. Maybe 500 lines of platform code, total."

"Every device UI—current AND future—comes from the CSA registry. New device type? It just works. No platform update required."

"Platform engineers can focus on what matters: performance, polish, integration. Not implementing thermostat UIs."

*Timing: 1.5 minutes*

<div style="page-break-after: always;"></div>

# Who Wins: Users

## One App. Full Control. No Compromises.

- **No more "download our app"**
- **Full device features in their preferred platform**
- **Consistent experience across all devices**
- **Vendor branding without vendor apps**

> "I just want to control my lights. I don't want 12 apps to do it."
> — Every smart home user

**SPEAKER NOTES:**

"Users are the ultimate winners here."

"They pick their favorite platform—Apple Home, Google Home, Amazon Alexa—and they're DONE. Every device they buy, full control, right there."

"No more hunting through vendor apps. No more remembering which app controls which device. No more managing 15 accounts and passwords."

"And they still get vendor branding and features. The Philips Hue experience. The Ecobee experience. Just... inside their preferred app."

*Timing: 1 minute*

<div style="page-break-after: always;"></div>

# Who Wins: CSA

## Control the Pace of Innovation

- **CSA publishes device type + standard module = instant support everywhere**
- **No more waiting for platform updates**
- **Certification revenue (module certification fees)**
- **Drives Matter adoption** (vendors choose Matter for MBX)
- **Fulfills the Matter promise**

**SPEAKER NOTES:**

"For CSA, this is strategic."

"Today, when CSA ratifies a new device type, nothing happens for users until Apple updates Home, Google updates Home, Amazon updates Alexa. That's 6-12 months, EACH."

"With MBX, CSA publishes the device type AND the standard module. Platforms pull it automatically. Users have full UI on day one."

"CSA controls the pace of innovation. Not platform release cycles."

"There's also a revenue opportunity: module certification fees. Every vendor submitting a branded module goes through certification."

"And strategically, vendors will choose Matter BECAUSE of MBX. 'I can get my brand in every platform without building apps? Sign me up.'"

*Timing: 1.5 minutes*

<div style="page-break-after: always;"></div>

# The Game Changer: Instant Device Support

![](timeline.png)

**SPEAKER NOTES:**

"Let me show you what this means for new device types."

Point to TOP (red):
"TODAY: CSA publishes a new device type in January 2025. Apple needs to update their Home app—6 to 12 months. Google, same. Amazon, same. Users are waiting until late 2025 for full support, IF the platforms prioritize it."

Point to BOTTOM (green):
"WITH MBX: CSA publishes the device type AND the standard module. Same day. Platforms pull from the registry. Users have full UI on day one."

"No app updates. No waiting. No hoping platforms prioritize your device category."

"This alone should make MBX compelling. New device categories—robot vacuums, pool controllers, EV chargers—users get full UI immediately."

*Timing: 1.5 minutes*

<div style="page-break-after: always;"></div>

# Proven Architecture

![](widgetkit.png)

**SPEAKER NOTES:**

"Now, some of you might be thinking: 'Running vendor code on our platform? That sounds risky.'"

"Here's the thing: Apple already does this. It's called WidgetKit."

Point to LEFT:
"WidgetKit: Third-party apps provide widget code. iOS renders it on the home screen. Sandboxed execution. Limited API. Platform-native rendering."

Point to RIGHT:
"MBX: Third-party vendors provide module code. Platforms render it in the home app. Sandboxed execution. Limited API. Platform-native rendering."

"SAME PATTERN."

"Apple ships WidgetKit to 1+ billion devices. Millions of widgets from thousands of developers. If Apple trusts sandboxed code for the home screen, platforms can trust it for device UI."

Read the tagline:
"WidgetKit is MBX for the home screen. MBX is WidgetKit for smart home devices."

*Timing: 2 minutes*

<div style="page-break-after: always;"></div>

# Security Model

## Built on Proven Principles

| Principle | Implementation |
|-----------|---------------|
| **Sandboxed Execution** | Lua VM with no file/network access |
| **Declarative Output** | Code produces UI description, not actions |
| **Platform Rendering** | Native frameworks render all UI |
| **CSA Certification** | Every module reviewed and signed |
| **Existing PKI** | Uses vendor's existing CSA certificates |
| **Revocation** | CSA can revoke malicious modules instantly |

**Privacy:** All rendering is LOCAL. No user data sent to vendors or CSA.

**SPEAKER NOTES:**

"Security is obviously critical. Here's the model."

"Modules run in a sandboxed Lua VM. No file system access. No network access. No device sensors. The ONLY thing they can do is produce a UI description and call the platform's Matter APIs."

"The platform does all the rendering. Vendors can't draw arbitrary pixels—they describe UI components, platforms render them natively."

"Every module goes through CSA certification. Automated analysis, resource profiling, human review. Then it's signed with the vendor's existing CSA certificate—same PKI they already use for device certification."

"If a module turns out to be malicious? CSA revokes it. Platforms stop loading it. Done."

"And critically: all rendering is LOCAL. On the user's device. No user data flows to vendors or CSA. Complete privacy."

*Timing: 1.5 minutes*

<div style="page-break-after: always;"></div>

# How It Works (Simplified)

![](architecture.png)

**SPEAKER NOTES:**

"Here's the architecture in 30 seconds."

"Vendor writes a Lua module. About 100 lines for a typical device. It describes the UI and what Matter commands to send when users interact."

"Module goes to the CSA registry. Certified, signed, stored."

"Platforms—Apple, Google, Amazon—download modules from the registry. They run the Lua in a sandboxed VM, get back a UI description, and render it with their native framework."

"Same module produces SwiftUI on iOS, Compose on Android, whatever Amazon uses. Native look and feel, everywhere."

"That's it. That's the whole architecture."

*Timing: 1 minute*

<div style="page-break-after: always;"></div>

# The Ask

## Establish the MBX Working Group

**Phase 1: Specification (3 months)**
- Formalize UI primitive set
- Define module format and APIs
- Specify security requirements

**Phase 2: Reference Implementation (6 months)**
- iOS reference runtime
- Android reference runtime
- Module development SDK

**Phase 3: Pilot Program (3 months)**
- 10 device vendors
- 2-3 platform partners
- Real-world validation

**SPEAKER NOTES:**

"So here's what we're asking for."

"Establish an MBX Working Group within CSA. We've done the design work—there's a 50-page technical specification ready for review."

"Phase 1: Formalize the specification. UI primitives, module format, security requirements. Three months with the right people in the room."

"Phase 2: Build reference implementations. iOS runtime, Android runtime, SDK for module developers. Six months."

"Phase 3: Pilot with real vendors and platforms. Ten device vendors, a couple platform partners. Validate it works in the real world."

"Twelve months from kickoff to production-ready specification and tooling."

*Timing: 1 minute*

<div style="page-break-after: always;"></div>

# Why Now

1. **Matter adoption is accelerating**
   - Billions of devices expected by 2027

2. **User frustration is mounting**
   - App fatigue limits smart home adoption

3. **Vendors want relief**
   - App development is expensive and distracting

4. **The technology is ready**
   - SwiftUI, Compose make native rendering trivial
   - Lua is battle-tested (Roblox: 70M+ daily users)

5. **The architecture is proven**
   - WidgetKit, server-driven UI at Airbnb/Netflix/Shopify

**SPEAKER NOTES:**

"Why now? Why is this the right moment?"

"Matter is taking off. We're going to see billions of Matter devices. The fragmentation problem will only get worse."

"Users are frustrated. 'Too many apps' is the number one complaint about smart homes. It's limiting adoption."

"Vendors are tired of app development. It's expensive, distracting from their core business, and they STILL can't reach users in the major platforms."

"The technology is ready. SwiftUI and Compose make native rendering easy. Lua is proven at massive scale—Roblox runs on it with 70 million daily users."

"And the architecture is proven. Apple does this with WidgetKit. Airbnb, Netflix, Shopify all use server-driven UI. We're not inventing anything—we're applying proven patterns to smart home."

*Timing: 1 minute*

<div style="page-break-after: always;"></div>

# The Vision

**One module. Every platform. Full branding.**

- Users pick ONE app and get EVERYTHING
- Vendors reach EVERY platform without building apps
- Platforms get richer ecosystems without engineering work
- CSA controls the pace of innovation

## Matter promised interoperability.
## MBX delivers it.

**SPEAKER NOTES:**

"Let me leave you with the vision."

"One module. Every platform. Full branding."

"Users pick their favorite app—Apple Home, Google Home, Amazon Alexa—and they get full control of every device with full vendor branding. Done."

"Vendors write one module—100 lines of Lua—and their brand appears everywhere. No apps to build or maintain."

"Platforms get a richer ecosystem. More devices, more features, more user satisfaction. Without lifting a finger for new device types."

"And CSA? CSA becomes the center of smart home UI. You publish a device type, it works everywhere, immediately."

"Matter promised interoperability. MBX delivers it."

*Timing: 1 minute*

<div style="page-break-after: always;"></div>

# Questions?

**Technical Specification:** Available upon request

**Contact:** [your contact info]

**Next Step:** Working group formation vote

**SPEAKER NOTES:**

"I'm happy to take questions. We also have a detailed technical specification—about 50 pages—available for anyone who wants to dig into the implementation details."

"The next step is a vote to form the MBX Working Group. I hope I've convinced you this is worth pursuing."

"Questions?"

*Timing: Remaining time for Q&A*

<div style="page-break-after: always;"></div>

# Appendix: Image Files

| Slide | Image File | Description |
|-------|-----------|-------------|
| 2 | `frustration.png` | Phone with 15+ app icons, frustrated user |
| 4 | `unification.png` | Phone with single Home app, devices orbiting |
| 5 | `MDUI_example_screens.png` | Four iPhone screens: Standard → Branded → Extended → Extended UI |
| 6 | `branded.png` | Three phones (Apple/Google/Amazon) showing Philips Hue UI |
| 7 | `workflow.png` | Fork → Brand → Submit → Done workflow |
| 9 | `platform_savings.png` | Without MBX vs With MBX engineering comparison |
| 12 | `timeline.png` | Today (6-12 months) vs With MBX (instant) |
| 13 | `widgetkit.png` | Apple WidgetKit ≈ MBX architecture comparison |
