---
title: Chapter 3 - Check Knowledge
bookCollapseSection: true
weight: 300
---

# Checking Knowledge

This is a test of questions embedded in the book.

## Question 1 - Multiple Choice with Text with one correct answer


{{ < mcq question="What is the capitol of the United States?" options="Washington D.C.|Paris|London|Beijing" correct_answer="Washington D.C." > }}

## Question 2 - True False Question


{{ < tf question="Chicago is in Ohio." answer=false > }}

## Question 3 - Sort the Paragraphs

{{ < sortparagraphs steps="Un|Deux|Trois|Quatre|Cinq" list="Deux|Quatre|Cinq|Un|Trois" > }}

## Question 4 - Audio Recorder

{{ < audiorecorder Question="Record your voice:" > }}

## Question 5 - Freewrite

{{ < freewrite Question="Write some stuff!" > }}

## Question 6 - Fill in the blanks

{{ < fillinblank Paragraph="Paris is in <input type="text" id="word1"> which is a country in <input type="text" id="word2">." words="document.getElementById("word1").value.trim()|document.getElementById("word2").value.trim()" answers="France|Europe" useranswers="word1|word2" > }}

## Question 7 - Match words
{{ < dragdrop questions="Je|Tu|Il/Elle/On|Nous|Vous|Ils/Elles" answers="ai|as|a|avons|avez|ont" > }}

## Question 8 - Highlight words
{{ < highlightwords paragraph="This is a paragraf with some mispeled words. Hilite the ones that are misspelled." incorrectWords="paragraf|mispeled|Hilite" > }}

## Question 9 - Multiple Choice with multiple correct answers

{{ < mcq2 Question="Which of these cities are in the US?" a1="Dallas" a2="London" a3="Madrid" a4="Seattle" correctOptions="Dallas|Seattle" > }}
