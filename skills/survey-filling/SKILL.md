# Fill surveys

Fill a customer feedback survey or questionnaire in the browser, following the user's standing answer rules, pausing on questions that cannot be answered honestly, and confirming with the user before submitting.

## Personal information

- Read `MEMORY.md` to get personal information.
- If no personal information is available, ask the user before filling any personal fields.

## Start the survey

- Accept the survey as a link, a receipt photo, or a certificate or survey code the user supplies, and read every visible detail from it before opening the survey.

- Open the survey with `browser.browse` as a new task, passing the exact URL and the exact code, and tell the browser task the language the user chose.

- If the entry page asks for an invitation type, pick the one that matches what the user supplied, such as a store receipt or a donor invitation card.

- Verify the code was accepted before answering anything, and report the entry requirements if the survey cannot be entered without a code.

## Answer with the standing rules

- Only fill required fields; leave optional fields blank, except always fill the membership card number when that field appears.

- For every satisfaction or rating question, randomly choose between the top two positive options, and vary the pick from question to question instead of always selecting the same one.

- For every open ended text question, write a brief positive comment in simple English.

- For any question asking what could be improved, write that everything is currently good and there is nothing particular to report.

- Fill personal details from `MEMORY.md` (or answers the user provided after being asked), and never invent a name, email address, phone number, postal code, birthday, or membership number.

- For a factual question with a neutral option such as don't remember, not applicable, or prefer not to answer, choose the neutral option.

- For a factual question with no neutral option, stop and ask the user for the answer instead of guessing.

- Keep working through the survey on its own until the last page, and stop there instead of submitting.

- For questions about staff, always answer that staff were friendly and polite.

- For the checkout question, always select self checkout.

- For questions asking whether you are a store employee, or whether you live with a store employee, always answer No.

- For the question asking whether you got everything you needed on this trip, always answer Yes.

- For the checkout duration question (from lining up or walking to the register through paying and collecting items), randomly select a time between 20 and 30 minutes.

## Standing defaults for Shoppers surveys

- For the question about which areas of the store were visited, always select Other Areas of the Store.

## Handle blocks and consent

- If the site shows a JavaScript alert or warning popup because of a wrong entry, take a screenshot, stop, and report it to the user.

- Leave any marketing or newsletter opt in unchecked, and if the form cannot be submitted without it, stop and get the user's explicit approval before checking it.

- Before checking a box that affirms the user read and agreed to terms and conditions, confirm with the user first.

- If the browser window dies mid survey, start a new browser task, check whether the session survived through cookies, and if it restarted, re enter the code and re answer everything from the recorded answers.

## Confirm and finish

- At the last page before submitting, report every answer given, flag any neutral or uncertain ones, and submit only after the user explicitly confirms.

- After submission, report the confirmation text and copy any coupon code or validation code exactly.

- Save any coupon received to the user's coupon file and delete expired entries from it, keeping only valid coupons.

## Websites

- [Value Village Listens](https://valuevillagelistens.com/) for Value Village receipt surveys. Carry the exact survey code into the browser task and verify it was accepted.

- [Shoppers Drug Mart Survey](https://www.surveysdm.com/) for Shoppers Drug Mart receipt surveys. Carry the exact certificate number into the browser task and verify it was accepted.

- For any other survey, use the link or receipt the user supplied, and never guess a survey URL from a business name.
