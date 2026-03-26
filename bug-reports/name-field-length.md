# Bug Report

## ID
BUG-003

## Title
Name field accepts more than 30 characters

## Severity
Medium

## Priority
Low

## Environment
Browser: Chrome 146  
OS: Windows 10

## Preconditions
User is on the feedback page

## Steps to Reproduce
1. Open https://bug-test.online/
2. Click "Обратная связь"
3. Enter more than 30 characters in the "Имя" field
4. Fill in other fields with valid data
5. Click "Отправить"

## Expected Result
System should show validation error for name length.

## Actual Result
System accepts input and sends the feedback form.

## Attachments
N/A
