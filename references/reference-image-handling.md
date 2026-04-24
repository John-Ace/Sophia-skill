# Reference Image Handling

## Purpose

Reference-led image requests need tighter control than normal image requests.

The main risk is accidental over-copying or uncontrolled style borrowing.

## Borrowing layers

Clarify exactly what should be borrowed:

- overall feeling
- composition
- color palette
- lighting
- pose or expression
- texture or material
- typography or title area
- spacing and density

## Non-borrowed layers

Also clarify what should remain different:

- subject
- scene structure
- props
- styling
- overall brand tone

## Rule

Do not simply say "I will reference this image."

State both:

- what is borrowed
- what is not borrowed

## Final prompt requirement

For reference-led work, the final prompt should restate the borrowing boundary directly so the model does not drift into full-style imitation.

## Safety principle

If the user seems to want too many layers borrowed at once, reduce the borrowing scope and prioritize the most important layer first.
