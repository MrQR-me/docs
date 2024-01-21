---
title: Pricing
layout: default
nav_order: 15
---

# **Pricing**{: .text-purple-000 }

## **MrQR**{: .text-purple-000 } Free Account
users have a limited profile and can request access and complete any forms on the **MrQR**{: .text-purple-000 } platform

### £0.00

## **MrQR**{: .text-purple-000 } Pro User Account including a Personal Site
users have a comprehensive profile, a personal site and can request access to complete any forms on the **MrQR**{: .text-purple-000 } platform

### ~~£2.49~~ / Month

(*while making improvements and adding exciting new features* **MrQR**{: .text-purple-000 } *pro user accounts are free - £0.00 / month untill we Launch in March 2024*)

## Additional **MrQR**{: .text-purple-000 } Site Licence
Manage and Share all your Items & Forms using the **MrQR**{: .text-purple-000 } Code or Link to any **MrQR**{: .text-purple-000 } registered user.

Approve **MrQR**{: .text-purple-000 } user requests to allow secured accesss to your items information & forms.

### £7.49 / Month / Site Licence

## **MrQR**{: .text-purple-000 } FormBuilder
Create, Edit & Duplicate you own forms to your own sites or share them globally as templates to the **MrQR**{: .text-purple-000 }  community

### Coming soon, will be available with a valid monthly site licence

<!-- Display the countdown timer in an element -->
<p id="demo"></p>

<script>
// Set the date we're counting down to
var countDownDate = new Date("Jan 5, 2024 15:37:25").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();

  // Find the distance between now and the count down date
  var distance = countDownDate - now;

  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the result in the element with id="demo"
  document.getElementById("demo").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";

  // If the count down is finished, write some text
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000);
</script>
