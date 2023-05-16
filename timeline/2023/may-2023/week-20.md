---
description: 15th May to 21st May 2023
---

# Week 20

## Monday, 15th May 2023

### Education Guild

Hosted by&#x20;



### Broadcast Ideation

Hosted by

## Tuesday, 16th May 2023

### Supervisory Council Community Call



### Governance Workgroup

Hosted by Felix Weber

#### Framework document

[link](https://docs.google.com/document/d/1VQvztaryoFQ\_vgY2u9dhKTsF7P\_pyDwD9K7CnDsxhNc/edit?usp=sharing)

[https://docs.google.com/document/d/1VQvztaryoFQ\_vgY2u9dhKTsF7P\_pyDwD9K7CnDsxhNc/edit?usp=sharing](https://docs.google.com/document/d/1VQvztaryoFQ\_vgY2u9dhKTsF7P\_pyDwD9K7CnDsxhNc/edit?usp=sharing)

#### Archiving comments

{% embed url="https://stackoverflow.com/questions/66103464/export-google-docs-comments-into-google-sheets-along-with-highlighted-text" %}

#### GPT Prompt

File upload to GPT

Generate a Js script that creates a button with the text ‘Submit File’ and inserts it into the DOM before an element with the class ‘.flex.flex-col.w-full.py-2.flex-grow.md:py-3.md:pl-4’. The button should have a green background color, white text color, 5px padding, no border, 5px border radius and 5px margin. The script should also create a progress element and insert it into the DOM before the same element. The progress element should have a width of 99%, height of 5px and a grey background color. Inside the progress element, there should be another div element representing the progress bar with a width of 0%, height of 100% and blue background color. When the button is clicked, it should create an input element of type ‘file’ that accepts ‘.txt’, ‘.js’, ‘.py’, ‘.html’, ‘.css’, ‘.json’ and ‘.csv’ files. Once a file is selected, using an async it should be read as text and split into chunks of size 15000. using async Each chunk should be submitted into a conversation by doing the following: async function submitConversation(text, part, filename) { const textarea = document.querySelector("textarea\[tabindex='0']"); const enterKeyEvent = new KeyboardEvent("keydown", { bubbles: true, cancelable: true, keyCode: 13, }); textarea.value = `Part ${part} of ${filename}: \n\n ${text}`; textarea.dispatchEvent(enterKeyEvent); }. The progress bar should be updated after each chunk is submitted within the for loop as follows progressBar.style.width = `${((i + 1) / numChunks) * 100}%`; and should also check if chatgpt is ready with this code: chatgptReady = false; while (!chatgptReady) { await new Promise((resolve) =＞ setTimeout(resolve, 1000)); chatgptReady = !document.querySelector( ".text-2xl ＞ span:not(.invisible)" Once all chunks have been submitted, the progress bar should turn blue.

#### Organic Governance Through the Logic of Holonic Systems

{% file src="../../../.gitbook/assets/kenric" %}

### Ambassador Townhall

Hosted by

### Process Guild

Hosted by&#x20;
