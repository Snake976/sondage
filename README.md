<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sondage</title>

<style>
body {
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(135deg, #eef2ff, #fde68a);
  margin: 0;
}

.container {
  max-width: 1000px;
  margin: 30px auto;
  padding: 20px;
}

h1 {
  text-align: center;
  color: #1e3a8a;
  margin-bottom: 30px;
}

.section {
  background: white;
  padding: 25px;
  border-radius: 20px;
  margin-bottom: 20px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.1);
}

.section h2 {
  color: #2563eb;
  margin-bottom: 15px;
}

.question {
  margin-bottom: 15px;
}

.options {
  margin-top: 5px;
}

.options label {
  margin-right: 15px;
}

button {
  width: 100%;
  padding: 15px;
  background: #2563eb;
  color: white;
  border: none;
  border-radius: 12px;
  font-size: 16px;
  cursor: pointer;
}

button:hover {
  background: #1d4ed8;
}

.success {
  display: none;
  text-align: center;
  color: green;
  font-size: 18px;
}
</style>
</head>

<body>

<div class="container">
<h1>Sondage de satisfaction</h1>

<form id="form">

<div class="section">
<h2>Partie 1 : Accueil et intégration</h2>

<div class="question">
1. As-tu été bien accueilli(e) ?
<div class="question"> 
Par le service RH :

<div class="options">
<label><input type="radio" name="q1"> Pas du tout</label>
<label><input type="radio" name="q1"> Moyennement</label>
<label><input type="radio" name="q1"> Bien</label>
<label><input type="radio" name="q1"> Très bien</label>
</div>
</div>
<div class="question"> 
Par ton propre service :

<div class="options">
<label><input type="radio" name="q1"> Pas du tout</label>
<label><input type="radio" name="q1"> Moyennement</label>
<label><input type="radio" name="q1"> Bien</label>
<label><input type="radio" name="q1"> Très bien</label>
</div>
</div>

<div class="question">
2. Le premier jour s’est-il bien déroulé ?
<div class="options">
<label><input type="radio" name="q2"> Pas du tout</label>
<label><input type="radio" name="q2"> Moyennement</label>
<label><input type="radio" name="q2"> Bien</label>
<label><input type="radio" name="q2"> Très bien</label>
</div>
</div>


3. As-tu reçu toutes les informations nécessaires ?
<div class="options">
<label><input type="radio" name="q3"> Oui</label>
<label><input type="radio" name="q3"> Partiellement</label>
<label><input type="radio" name="q3"> Non</label>
</div>
</div>
<div class="question"> 
Quelles améliorations pourriez-vous suggérer ? :
<div class="question">
Points positifs :
<textarea name="q19"></textarea>
</div>

<div class="section">
<h2>Partie 2 : Compréhension du poste</h2>

<div class="question">
1. Comprends-tu ton rôle dans la structure ?
<div class="options">
<label><input type="radio" name="q4"> Pas du tout</label>
<label><input type="radio" name="q4"> Moyennement</label>
<label><input type="radio" name="q4"> Bien</label>
<label><input type="radio" name="q4"> Très bien</label>
</div>
</div>

<div class="question">
2. Les objectifs sont-ils clairs ?
<div class="options">
<label><input type="radio" name="q5"> Oui</label>
<label><input type="radio" name="q5"> Non</label>
<label><input type="radio" name="q5"> Partiellement</label>
</div>
</div>

<div class="question">
3. Sais-tu à qui t’adresser en cas de difficulté ?
<div class="options">
<label><input type="radio" name="q6"> Oui</label>
<label><input type="radio" name="q6"> Non</label>
</div>
</div>

</div>

<div class="section">
<h2>Partie 3 : Environnement et ambiance</h2>

<div class="question">
1. Te sens-tu à l’aise dans ton environnement ?
<div class="options">
<label><input type="radio" name="q7"> Pas du tout</label>
<label><input type="radio" name="q7"> Moyennement</label>
<label><input type="radio" name="q7"> Bien</label>
<label><input type="radio" name="q7"> Très bien</label>
</div>
</div>

<div class="question">
2. Selon toi, l'ambiance de travail est-elle ?
<div class="options">
<label><input type="radio" name="q8"> Tendue</label>
<label><input type="radio" name="q8"> Anxieuse</label>
<label><input type="radio" name="q8"> Conviviale</label>
<label><input type="radio" name="q8"> Motivante</label>
</div>
</div>

<div class="question">
3. Te sens-tu intégré(e) dans l’équipe ?
<div class="options">
<label><input type="radio" name="q9"> Pas du tout</label>
<label><input type="radio" name="q9"> Moyennement</label>
<label><input type="radio" name="q9"> Bien</label>
<label><input type="radio" name="q9"> Très bien</label>
<div class="question"> 
Quelles améliorations pourriez-vous suggérer ? :
<div class="question">
Points positifs :
<textarea name="q19"></textarea>
</div>
</div>
</div>

</div>

  <div class="section">
<h2>Partie 4 : Management</h2>

<div class="question">
Manager à l’écoute ?
<label><input type="radio" name="q12"> Toujours</label>
<label><input type="radio" name="q12"> Parfois</label>
<label><input type="radio" name="q12"> Jamais</label>
</div>

<div class="question">
Reçois-tu des encouragements ?
<label><input type="radio" name="q13"> Oui</label>
<label><input type="radio" name="q13"> Parfois</label>
<label><input type="radio" name="q13"> Non</label>
</div>

<div class="question">
Te sens-tu reconnu(e) ?
<label><input type="radio" name="q14"> Oui</label>
<label><input type="radio" name="q14"> Non</label>
<label><input type="radio" name="q14"> Parfois</label>
<div class="question"> 
<div class="question">
<label>Quel style de management te semble le plus adapté à tes besoins ? (2 choix max)</label>
<div style="display: flex; flex-direction: column; gap: 10px;">
<label><input type="checkbox" name="mngt" value="participatif"> Participatif (on décide ensemble)</span>
<span><input type="checkbox" name="mngt" value="autonome"> Délégatif (on me fait confiance sur l'exécution)</span>
<span><input type="checkbox" name="mngt" value="cadre"> Directif (besoin de consignes très claires)</span>
<span><input type="checkbox" name="mngt" value="coach"> Coach (besoin d'accompagnement et de formation)</span>
    </div>
</div>
</div>

<div class="section">
<h2>Partie 5 : Organisation</h2>

<div class="question">
Ta charge de travail est :
<label><input type="radio" name="q15"> Faible</label>
<label><input type="radio" name="q15"> Correcte</label>
<label><input type="radio" name="q15"> Élevée</label>
</div>

<div class="question">
Les outils sont adaptés ?
<label><input type="radio" name="q16"> Oui</label>
<label><input type="radio" name="q16"> Non</label>
<label><input type="radio" name="q16"> Partiellement</label>
</div>
</div>

<div class="section">
<h2>Partie 6 : Bien-être</h2>

<div class="question">
Niveau de stress :
<label><input type="radio" name="q17"> Faible</label>
<label><input type="radio" name="q17"> Moyen</label>
<label><input type="radio" name="q17"> Élevé</label>
  <div class="question">
Si tu ressens du stress, quelle en est la cause principale ? :
<textarea name="q19"></textarea>
</div>
</div>

<div class="question">
Motivation :
<label><input type="radio" name="q18"> Élevée</label>
<label><input type="radio" name="q18"> Moyenne</label>
<label><input type="radio" name="q18"> Faible</label>
</div>
</div>

<div class="section">
<h2>Partie 7 : Retour d'experience</h2>

<div class="question">
Points positifs :
<textarea name="q19"></textarea>
</div>

<div class="question">
Axes d’amélioration :
<textarea name="q20"></textarea>
</div>

<div class="question">
Suggestions :
<textarea name="q21"></textarea>
</div>
</div>

<button type="submit">Envoyer</button>

</form>

<div class="success" id="success">Réponse enregistrée ✅</div>

</div>

<script>
document.getElementById('form').addEventListener('submit', function(e){
e.preventDefault();

const data = new FormData(this);
let obj = {};

data.forEach((v,k)=> obj[k]=v);

let responses = JSON.parse(localStorage.getItem('responses')) || [];
responses.push(obj);
localStorage.setItem('responses', JSON.stringify(responses));

document.getElementById('success').style.display = 'block';
this.style.display = 'none';
});
</script>

</body>
</html>
