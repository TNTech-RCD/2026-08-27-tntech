---
# More detailed instructions (including how to fill these variables for an # online workshop) are available at https://carpentries.github.io/workshop-template/customization/index.html#yaml-header
# Required variables
venue: "Tennessee Tech University"        # brief name of the institution that hosts the workshop without address (e.g., "Euphoric State University")
building: "Bruner Hall, Rm 126"
address: "Bruner Hall, Room 126, 110 University Drive, Cookeville, TN 38501"
streetaddress: "110 University Drive"      # full street address of workshop (e.g., "Room A, 123 Forth Street, Blimingen, Euphoria"), videoconferencing URL, or 'online'
citystatezip: "Cookeville, TN 38501"
country: "us"      # lowercase two-letter ISO country code such as "fr" (see https://en.wikipedia.org/wiki/ISO_3166-1#Current_codes) for the institution that hosts the workshop
language: "en"     # lowercase two-letter ISO language code such as "fr" (see https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) for the workshop
latitude: "36.1782"     # decimal latitude of workshop venue - this should be a number greater than or equal to -90, and less than or equal to 90 (use https://www.latlong.net/)
longitude: "-85.5085"    # decimal longitude of the workshop venue - this should be a number greater than or equal to -180, and less than or equal to 180 (use https://www.latlong.net)
humandate: "Select Thursdays"    # human-readable dates for the workshop (e.g., "Feb 17-18, 2020")
humantime: "6:00–9:00 PM Central Time"    # human-readable times for the workshop e.g., "9:00 am - 4:30 pm CEST (7:00 am - 2:30 pm UTC)"
startdate: 2026-08-27      # machine-readable start date for the workshop in YYYY-MM-DD format like 2015-01-01
enddate: 2026-11-19        # machine-readable end date for the workshop in YYYY-MM-DD format like 2015-01-02
instructor: ["Sharon Colson"] # boxed, comma-separated list of instructors' names as strings, like ["Kay McNulty", "Betty Jennings", "Betty Snyder"]
helper: ["Trevor Clark"]     # boxed, comma-separated list of helpers' names, like ["Marlyn Wescoff", "Fran Bilas", "Ruth Lichterman"]
email: ["scolson@tntech.edu", "sw-tlclark@tntech.edu"]    # boxed, comma-separated list of contact email addresses for the host, lead instructor, or whoever else is handling questions, like ["marlyn.wescoff@example.org", "fran.bilas@example.org", "ruth.lichterman@example.org"]

# Optional variables
collaborative_notes:  # URL for the workshop collaborative notes, e.g. an Etherpad or Google Docs document (e.g., https://pad.carpentries.org/2015-01-01-euphoria)
eventbrite:           # alphanumeric key for Eventbrite registration, e.g., "1234567890AB" (if Eventbrite is being used)
what3words:           # what3words (https://what3words.com) address of the workshop venue, without leading slashes e.g. "globe.lessening.computers"

### Workshop Series Content ###
workshop_url: "https://www.rcd.tntech.edu/2026-08-27-tntech/"
workshop_display_url: "www.rcd.tntech.edu/2026-08-27-tntech"
workshop_qr_code: "/assets/img/workshop/workshop-qr-code.png"

workshop_outcomes:
  - "Work confidently at the command line"
  - "Track and share work with Git"
  - "Analyze data with Python or R"
  - "Build reproducible workflows"

certificate:
  enabled: true
  title: "Certificate of Achievement"
  invitation: "Complete the pathway"
  description: "Complete Unix, Git, and one full Python or R lesson. That's 12 instructional hours with no homework."
  
  pathway_heading: "Complete four meetings. Show what you learned."
  pathway_description: >-
    Attend one Unix offering, one Git offering, and both meetings of any programming lesson.

  requirements:
    - count: 1
      label: "Unix"

    - count: 1
      label: "Git"

    - count: 2
      label: "Programming"

workshop_introduction: >-
  Free beginner-friendly, hands-on workshops for Tennessee Tech students,
  faculty, staff, and researchers who want to work more confidently with
  data, code, and computational tools.

workshop_requirements:
  heading: "Come ready to learn"
  description: >-
    Bring a Mac, Windows, or Linux laptop and its charging cable.
    Workshop-specific setup instructions will be available from each
    event listing.

  default_laptop_support: >-
    Need a laptop? Tennessee Tech students and employees may request
    information about laptop availability through the ITS Help Desk on
    the main floor of Volpe Library.

  default_capacity: 20

  default_registration_notice: >-
    Advance registration is requested. 


# Digital signage
signage_kicker: "Free Fall 2026 Workshop Series"
signage_headline: "Build practical"
signage_headline_emphasis: "computing foundations."

signage_outcomes:
  - "Use Unix and Git • Analyze data with Python or R"
  - "Build reproducible computational workflows"

signage_short_time: "6–9 PM"
signage_experience: "Beginners welcome"
signage_presenter: "Research Computing & Data"

# DON'T CHANGE THIS
layout: workshop
series_landing: true
---

{% include series-page.html %}
