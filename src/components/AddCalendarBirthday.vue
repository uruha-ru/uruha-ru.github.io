<template>
    <a rel="noopener" target="_blank" href="/ics/birthday.ics">iCalendar</a>
    <form action="https://outlook.live.com/calendar/0/action/compose" method="get" target="_blank">
        <input type="hidden" name="allday" value="true">
        <input type="hidden" name="subject" value="Birthday of Uruha Rushia">
        <input type="hidden" name="startdt" value="2019-01-22T00:00:00+09:00">
        <input type="hidden" name="enddt" value="2019-01-23T00:00:00+09:00">
        <input type="hidden" name="subject" value="Birthday of Uruha Rushia">
        <input type="hidden" name="path" value="/calendar/action/compose">
        <input type="hidden" name="rru" value="addevent">
        <input type="submit" value="Outlook">
    </form>
    <form action="https://outlook.office.com/calendar/action/compose" method="get" target="_blank">
        <input type="hidden" name="allday" value="true">
        <input type="hidden" name="subject" value="Birthday of Uruha Rushia">
        <input type="hidden" name="startdt" value="2019-01-22T00:00:00+09:00">
        <input type="hidden" name="enddt" value="2019-01-23T00:00:00+09:00">
        <input type="hidden" name="repeat" value="yearly">
        <input type="hidden" name="subject" value="Birthday of Uruha Rushia">
        <input type="hidden" name="path" value="/calendar/action/compose">
        <input type="hidden" name="rru" value="addevent">
        <input type="submit" value="Microsoft 365">
    </form>
    <form action="https://calendar.google.com/calendar/render" method="get" target="_blank">
        <input type="hidden" name="action" value="TEMPLATE">
        <input type="hidden" name="dates" value="20190122/20190122">
        <input type="hidden" name="ctz" value="Asia/Tokyo">
        <input type="hidden" name="text" value="Birthday of Uruha Rushia">
        <input type="hidden" name="recur" value="RRULE:FREQ=YEARLY">
        <input type="hidden" name="sf" value="true">
        <input type="submit" value="Google Calendar">
    </form>
</template>

<script setup lang="ts">
</script>

<style scoped>
form {
    display: inline-block;
}

form>input[type="submit"] {
    background: transparent;
    border: none;
    padding: 0;
    text-decoration: underline;
    color: rgb(0, 130, 200);
    cursor: pointer;
    margin-left: 8px;
}

a:link,
a:visited {
    color: rgb(0, 130, 200);
    text-decoration: underline;
    margin-left: 8px;
}
</style>