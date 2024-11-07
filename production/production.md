# Extension of duration based on hours and days

### Overview

   Atendees will be able to extend the duration of their lab based Minutes, Hours and Days 

### Prerequisites

- Before enabling and configuring the duration extention feature in ODL, ensure you have the following prerequisite:
  
  Admin access to [CloudLabs Admin Portal](https://admin.cloudlabs.ai/) (If access is unavailable, kindly reach out to your point of contact or [CloudLabs Support](https://docs.cloudlabs.ai/RequestSupport)).

### Enabling the duration extention feature in ODL

1. Log in to the CL portal and navigate to the required tenant (WIZ). On the left-hand side of the page, you will see the On Demand Labs section.

2. Navigate to the **ODL (1)** section in the left menu and click on the **edit (2)** button.

   ![](./img/01.png)

3. Scroll down to the **Allow User to Extend lab** section and enable the checkbox. 

   ![](./img/02.png)

4. Then select the required duration parameters from the dropbox for **Max Limit of Duration Extension by User** and **Allowed Extend Duration By Attendee** as per your requirement with appropriate values.

   ![](./img/03.png)



**Note:** The Max Limit should be an exact multiple of the Allowed Extend Duration to ensure that any extensions granted follow a consistent, repeatable pattern without remainder.


### Example Calculation

Suppose we set the following:

1. **Max Limit of Duration Extension by User** = 180 minutes
2. **Allowed Extend Duration By Attendee** = 30 minutes

For the setting to be valid, the **Max Limit (180 minutes)** should be evenly divisible by the **Allowed Extension (30 minutes)**. Here’s how we calculate it:


   ![](./img/3.1.png)

Since 6 is a whole number, 180 is a multiple of 30, so this configuration is **valid**.

---

### Example of an Invalid Configuration

Now, let’s try with:

1. **Max Limit of Duration Extension by User** = 175 minutes
2. **Allowed Extend Duration By Attendee** = 30 minutes


   ![](./img/3.2.png)


Since 5.83 is not a whole number, 175 is **not** a multiple of 30, making this configuration **invalid**.

---

5. Then click on the **Submit** button.

   ![](./img/04.png)




