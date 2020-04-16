---
description: Use this option on the main menu to preview how the contents that you are preparing will look before you publish them, or use it to simultaneously view the content of different segments.
---

# Test lines

## Preview changes

There is currently no web version for Explore so it is not yet possible to directly see how the content looks before publishing it.

However, every time you make a change to a layout (add or remove a module, edit the order of the modules), that layout changes to a **MODIFIED** status. In this status you can see those changes from your mobile app, as long as you have provided your mobile number to the NOVUM team of your OB so that they can add it to a specific list and you can see the changes before publishing the layout.

In addition, from **Test lines** you are able to view different configurations of segments from the same device, without needing to change line or have various MSISDNs.

## Create a test line

Access the **Explore > Test lines** menu and click on **CREATE A NEW TEST LINE**.

![](.gitbook/assets/image%20%2858%29.png)

In the **Create test line** window, fill in the following fields:

![](.gitbook/assets/image%20%2815%29.png)

**Phone number**. From the list, select the phone number that you want to perform the test on.

**Layout type**. Select one or more layouts to test the content.

**Microsegment**. Indicate the microsegments you want to apply to your test line. Write the names of the microsegments, separated by a comma and a space.

Example:

`microsegment1, microsegment2, microsegment3`

🔅 This is an optional field.

Click **NEXT** to continue. Select the state in which you wish to perform the test, depending on your objective:

![](.gitbook/assets/test_line_status.png)

#### Display multiple segments

- **Published**. You will see the design exactly as users are seeing it at that moment in time, with the advantage that you can also simultaneously view several other segments (those selected in **Layout type**), regardless of the segment of your mobile line.

#### Preview content before publishing

- **Draft**. You will see the design exactly as it is stored in the CMS at that time, even if it is not published. Use this option to preview a configuration before publishing it, ensuring that users will view it as you want them to.

{% hint style="danger" %} Please note that in test mode some *cards* links may not work properly. {% endhint %}
