# LeakInspector 🎇

LeakInspector is an add-on that warns and protects against personal data exfiltration. We developed LeakInspector to help publishers and end-users to audit third parties that harvest personal information from online forms without their knowledge or consent.

It has the following features:
 1. Blocks requests containing personal data extracted from the web forms and highlights related form fields by showing add-on's icon.
 2. Logs technical details of the detected sniff and leak attempts to console to enable technical audits. The logged information includes the value and XPath of the sniffed input element, the origin of the sniffer script, and details of the leaky request such as the URL and the POST data.
 3. A user interface where recent sniff and leak attempts are listed, along with the tracker domain, company and tracker category. The user interface module is based on code taken from [DuckDuckGo’s Privacy Essentials add-on](https://chrome.google.com/webstore/detail/duckduckgo-privacy-essent/bkdgflcldnnnapblkhphbgpggdiikppg?hl=en).
 
Our attempts to publish the add-on on the Chrome Web Store failed, because new uploads of Manifest v2 add-ons are not accepted. For leak detection, our add-on requires access to network request details, which will be disallowed in Manifest v3. ~~We are working on publishing the add-on for Firefox.~~ Our attempts to publish the add-on for Firefox [have failed](https://github.com/leaky-forms/leak-inspector/issues/13).

⚠️ The add-on is a proof-of-concept. It has not been extensively tested. Please use at your own discretion.

📖 This work is part of an [academic paper](https://homes.esat.kuleuven.be/~asenol/leaky-forms/leaky-forms-usenix-sec22.pdf). For a more detailed overview visit the **[project's homepage](https://homes.esat.kuleuven.be/~asenol/leaky-forms/)**. 


https://user-images.githubusercontent.com/48864422/167825572-7465e8a5-35f6-4fea-a2fa-aee247d78991.mp4

