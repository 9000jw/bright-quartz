---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: '4rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: hero
    content:
      title: Templergraben 39
      text: Evangelisches Studentenwohnheim
      primary_action:
        text: Bewirb dich fürs Wohnheim
        url: bewerbung/
    design:
      css_class: "dark"
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: blaueshaus.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false

  - block: stats
    id: stats
    content:
      items:
        - statistic: "23"
          description: |
            Mitbewohnis
        - statistic: "75+"
          description: |
            Jahre Selbstverwaltung
        - statistic: "100%"
          description: |
            Gemeinschaft
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-700 text-white"

      columns: "3"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        
  - block: features
    id: features
    content:
      title: Wie funktioniert das T39?
      text: Das T39 ist im Prinzip eine große WG mit 23 Bewohnern und ein paar Besonderheiten.
      items:
        - name: Miete
          icon: hero/wallet
          description: Formal ist die Evangelischen Kirche im Rheinland freier Träger des Gebäudes. Das bedeutet, die Kirche ist Eigentümer, verlangt aber keine Abgaben von uns. Weiter haben wir im Gegensatz zu anderen Wohnheimen keine Angestellten wie Reinigungsfachkräfte oder einen Hausmeister. Somit bleiben im wesentliche Grundbesitzabgaben an die Stadt Aachen und die Kosten für Wasser, Strom und Gas.
        - name: Hausarbeiten
          icon: hero/wrench
          description: Wie bereits im vergangenen Abschnitt erwähnte, gibt es weder bezahlte Reinigungskräfte, Hausmeister, noch einen Vermieter im herkömmlichen Sinne. Das T39 ist selbstverwaltet, was in Nordrhein-Westfalen einzigartig ist. Dadurch haben wir eine Menge Freiheiten, die zwangsläufig auch mit Verpflichtungen einhergehen. Dazu wird zu Beginn jedes Semesters eine Hausverwaltung aus drei Mitbewohnern gewählt, die Aufgaben verteilt und sich um die Belange des Hauses kümmert. Weitere Details siehst Du in unserem <strong><ins><a href="https://wiki.t39.rwth-aachen.de/wiki/index.php?title=Hauptseite"> hausinternen Wiki </a></ins></strong>

        - name: Doppelzimmer
          icon: hero/users
          description: Eine weitere wissenswerte Eigenart des T39 sind die Doppelzimmer im Erdgeschoss. Jeder Neuzugang wohnt für die erste Zeit im Doppelzimmer und zieht erst später in ein Einzelzimmer in eine der oberen Etagen. Obwohl viele Menschen anfangs überrascht darauf reagieren, hat sich dies bis heute bewährt. Die Bewohner haben so die Möglichkeit, in Sachen Gemeinschaft vieles zu lernen. Wichtig sind hier Flexibilität und Sensibilität im Umgang mit anderen Menschen. Dies ist auch der Geist, der als Grundidee über dem T39 schwebt und den enormen Zusammenhalt ausmacht. Die Miete im Doppelzimmer beträgt zurzeit 96 Euro.
        - name: Engagement
          icon: hero/user-group
          description: Prinzipiell fallen im T39 verschiedenste Aufgaben an. Wird beispielsweise eine Renovierung beschlossen, werden Ideen gesammelt, die Ausführung und Materialbeschaffung geplant und schlussendlich die Renovierung umgesetzt. Ausserdem gibt es dauerhafte Aufgaben wie die Server Administration oder die Verantwortung für einen der Gemeinschaftsräume. Jeder kann also seine Ideen, Stärken und Projekte umsetzen. Wir freuen uns auf deine.
        - name: Die Gemeinschaftsräume
          icon: hero/rectangle-group
          description: Das T39 besteht natürlich nicht nur aus Einzel- und Doppelzimmern. Als Gemeinschaftsräume haben wir unser Wohnzimmer, die Küche und unseren kleinen Garten zur Verfügung. Hier entstehen gemeinschaftliche Aktionen, wie z.B. gemeinsames Kochen, abendliches Zusammensitzen und verschiedene gemeinsam organisierte Feten, wie die jährlich stattfindenden Feuerzangenbowle und Cocktailparty.
    design:
      spacing:
          margin: 2 rem
---
