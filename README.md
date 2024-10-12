# Popkitu
Oh, hello there! Welcome to the official Popkitu GitHub repository!

# Overview
Popkitu is the official XML specification and parser for AntiRaid. It translates XML into Luau code to enhance user experience, providing an easier alternative for those unfamiliar with Luau.

# Key Features
- IntelliSense: Get real-time suggestions and autocompletions as you write your XML, making coding faster and more intuitive.
- Real-Time Debugger: Easily identify and fix issues with our built-in real-time debugging tools.
- Very Easy Syntax: XML syntax is straightforward and user-friendly, making it accessible for everyone.
- Extremely Fast: Popkitu is optimized for speed, ensuring quick parsing and processing of XML data.

# Warning ⚠️
This project is still extremely new and is extremely unstable. Production usage is not recommended.

# Usage
Here’s an example of how to structure your XML for use with Popkitu:
```xml
<DiscordMessage>
    <EmbedBuilder>
        <Title>Captcha</Title>
        <Description>Please prove that you are not a pesky robot. We do not take robots too kindly around here!</Description>
        <ShortImage src="https://antiraid.xyz/logo.webp"/>
        <BigImage src={captcha}/>
    </EmbedBuilder>
</DiscordMessage>
```
            
# LICENSE
This project is licensed under the AGPL (Affero General Public License). See the LICENSE file for details.
