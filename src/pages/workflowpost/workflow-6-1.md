---
templateKey: workflow-page
title: workflow-6
workflowjson:
  data: >
    [{"title":"Event Details","tabTitle":"Event Details","subHeading":"This is
    sub
    heading","content":[{"title":"Gender","name":"gender","type":"radio","value":[],"placeHolder":"","isRequired":false,"id":"gender","notice":"Choose
    Your
    hobby","options":[{"value":"Male","label":"Male"},{"value":"Female","label":"Female"}]},{"title":"Hobby","type":"checkbox","name":"hobby","isRequired":false,"value":[],"notice":"Choose
    Your
    hobby","id":"hobby","options":[{"value":"Sports","label":"Sports"},{"value":"Music","label":"Music"},{"value":"Reading","label":"Reading"},{"value":"Driving","label":"Driving"},{"value":"Dancing","label":"Dancing"}]},{"title":"Email","name":"email","type":"text","isRequired":true,"value":"","placeHolder":"Your
    Email","notice":"We don't share email","errorMessage":"Please enter your
    email","id":"email","validation":[{"regEx":{},"message":"Please enter valid
    email"}]},{"title":"Title","name":"title","type":"text","value":"","placeHolder":"Your
    Name","isRequired":false,"id":"title","notice":"Title for this Event
    Defination, Events and Alerts created from it.","errorMessage":"Please enter
    your
    name"},{"title":"Description(Optional)","name":"description","type":"textarea","isRequired":false,"value":"","placeHolder":"","notice":"Longer
    description for this Event Definition.","errorMessage":"Please enter your
    name","id":"description"},{"title":"Subject","name":"subject","type":"text","isRequired":false,"value":"","placeHolder":"Subject","notice":"","id":"subject"},{"title":"Priority,"type":"select","name":"priority","isRequired":false,"value":"","notice":"Choose
    the priority for Events create from this
    Definition.","id":"priority","options":[{"value":"","label":"Select"},{"value":"0","label":"Low"},{"value":"1","label":"High"},{"value":"3","label":"Normal"}]}]},{"title":"Event
    Condition","tabTitle":"Condition","subHeading":"Configure how Graylog should
    create Events of this kind. You can later use those Events as input on other
    Conditions, making it possible to build powerful Conditions based on
    others.","content":[{"title":"Condition
    Type","name":"conditiontype","type":"select","isRequired":false,"value":"","notice":"Choose
    the type of Condition for this
    Event.","id":"condition1","options":[{"value":"0","label":"Low"},{"value":"1","label":"High"},{"value":"2","label":"Normal"}]}]},{"title":"Title","tabTitle":"Fields","subHeading":"","content":[{"title":"Name","name":"name","type":"text","isRequired":false,"value":"","placeHolder":"Your
    Name","notice":"","id":"name"},{"title":"Email","name":"email","type":"text","isRequired":false,"value":"","placeHolder":"Your
    Email","notice":"We don't share
    email","validation":[{"regEx":{},"message":"Please enter valid
    email"}],"id":"email1"},{"title":"Contact
    Number","name":"contact","type":"text","isRequired":false,"value":"","placeHolder":"Your
    Contact Number","notice":"Enter your 10 digits contact
    number","id":"contact"},{"title":"Address(Optional)","name":"address","type":"textarea","isRequired":false,"value":"","placeHolder":"","notice":"","id":"address"},{"title":"Birth
    Date","name":"birthdate","type":"DATE","isRequired":false,"value":"","placeHolder":"","notice":"","id":"birtdate"},{"title":"Gender","name":"gender","type":"radio","value":"","placeHolder":"","isRequired":false,"notice":"","options":[{"value":"0","label":"Male"},{"value":"1","label":"Female"}],"id":"gender1"}]}]
---
