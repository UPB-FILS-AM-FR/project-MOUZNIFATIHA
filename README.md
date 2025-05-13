<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">

  
</head>
<body>

  <h1>Projet Arduino : Détecteur de Son avec LED et Buzzer</h1>
  <h3> Nom : MOUZNI</h3>
 <h3> Prenom : Fatiha</h3>
  <h2>1. Description du projet</h2>
  <p>Ce projet utilise un capteur sonore pour mesurer le niveau de bruit ambiant. Trois LED indiquent le niveau :</p>
  <ul>
    <li><strong>LED verte</strong> : bruit faible</li>
    <li><strong>LED jaune</strong> : bruit moyen</li>
    <li><strong>LED rouge + buzzer</strong> : bruit fort</li>
  </ul>

  <h2>2. Motivation</h2>
  <p>Ce projet peut être utilisé comme :</p>
  <ul>
    <li>Indicateur de niveau sonore dans une bibliothèque ou un bureau</li>
    <li>Détection de bruit anormal</li>
    <li>Apprentissage des capteurs analogiques avec Arduino</li>
  </ul>

  <h2>3. Composants nécessaires</h2>
  <table>
    <thead>
      <tr><th>Composant</th><th>Quantité</th></tr>
    </thead>
    <tbody>
      <tr><td>Arduino Uno/Nano</td><td>1</td></tr>
      <tr><td>Capteur de son </td><td>1</td></tr>
      <tr><td>LED verte</td><td>1</td></tr>
      <tr><td>LED jaune</td><td>1</td></tr>
      <tr><td>LED rouge</td><td>1</td></tr>
      <tr><td>Résistances 220Ω</td><td>3</td></tr>
      <tr><td>Buzzer </td><td>1</td></tr>
      <tr><td>Breadboard et câbles</td><td>1 kit</td></tr>
    </tbody>
  </table>

  <h2>4. Schéma de câblage</h2>
  <p>Connexion des composants :</p>
  <ul>
    <li>Capteur son AO → A0 (Arduino)</li>
    <li>Capteur son VCC → 5V</li>
    <li>Capteur son GND → GND</li>
    <li>LED verte → Pin 2</li>
    <li>LED jaune → Pin 3</li>
    <li>LED rouge → Pin 4</li>
    <li>Buzzer → Pin 5</li>
  </ul>
</body>
</html>
