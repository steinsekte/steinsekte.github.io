---
title: Mitglied werden
---

<script>
function check(form) {
    if (form.name.value=='' || form.email.value=='' || form.bew.value=='') {
        alert('Bitte alle Felder ausfüllen'); 
        return false; 
    }
    return true;   
}
</script>
<form method="POST" 
    action="mailto:labern@steinnsekte.xyz?subject="Mitglied+werden" 
    enctype="text/plain"
    onsubmit="return check(this);">

    <label for="name">Name</label>
    <input type="text" name="name">

    <label for="email">Email</label>
    <input type="text" name="email">

    <label for="bew">Bewerbung</label>
    <textarea name="bew" rows="5"></textarea>

    <div>
        <button type="submit">Abschicken</button>
    </div>
</form>