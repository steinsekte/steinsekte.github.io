---
title: Mitglied werden
---

Das Leben ohne MitSTEINe ist doch sinnlos. Darum werde schnell Mitglied bei den STEINen. Tu's! Uns fällt ein STEIN vom Herzen :) 

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
    action="https://lena.pro/reg.php" 
    enctype="application/x-www-form-urlencoded"
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