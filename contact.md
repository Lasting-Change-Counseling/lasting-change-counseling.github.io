---
layout: page
title: Contact
permalink: /contact/
---

TODO: 
 - [ ] [Clear and accessible contact Info](https://www.joinheard.com/articles/11-must-haves-for-your-therapy-website-tips-from-experts#clear-and-accessible-contact-info)
 - [ ] Form doesn't work yet

{{ site.title }} <br />
{{ site.name }} <br />
[{{ site.address }}](http://maps.google.com/?q={{ site.address }}) <br />
[{{ site.email }}](mailto:{{ site.email }}) <br />
[{{ site.phone }}](tel:{{ site.phone }}) <br />

<form class="" target="_blank" enctype="multipart/form-data" action="https://formkeep.com/f/exampletoken" accept-charset="UTF-8" method="post">
  <fieldset>
    <label for="First_Name">First Name</label>
    <input type="text" name="First Name" id="First_Name" class="form-control" />

    <br />

    <label for="Last_Name">Last Name</label>
    <input type="text" name="Last Name" id="Last_Name" class="form-control" />

    <br />
    
    <label title="required" for="Email">Email *</label>
    <input type="email" name="Email" id="Email" required="required" placeholder="example@example.com" class="form-control" />
    
    <br />
    
    <label for="Phone">Phone</label>
    <input type="tel" name="Phone" id="Phone" placeholder="+1 (303) 867-5309" class="form-control" />

    <br />

    <label for="Reason">Reason *</label>
    <select name="Reason" id="Reason" required="required" class="form-control">
      <option value="">Choose</option>
      <option value="Appointment">Book an appointment</option>
      <option value="Information">Request more information</option>
      <option value="Other">Other</option>
    </select>

    <br />

    <label title="required" for="Message">Message *</label>
    <textarea name="Message" id="Message" required="required" class="form-control">Your message here.</textarea>

    <br />

    <input type="submit" value="Submit" class="btn btn-block btn-primary" data-disable-with="Submit" />
  </fieldset>
</form>