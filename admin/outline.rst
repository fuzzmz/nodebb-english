Functii administrative
========================

.. nota::

    Aceste documente nu sunt la zi. Daca sunteti interesati sa updatati documentatia (preferabil cu screenshot-uri) ne puteti spune pe `forumul comunitatii <https://community.nodebb.org>`_ deoarece planuim refacerea design-ului ACP-ului in curand.


**Pentru a accesa zona administrativa** (daca sunteti admin): `http://your_nodebb_domain.com/admin`

**Meniul Principal** (toate pot fi accesate usor prin alte mijloace)
  * NodeBB ACP (Zona de control administrativ: pagina aceasta)
    * `http://your_nodebb_domain.com/admin/index` (vezi Acasa mai jos)
  * Forum
    * `http://your_nodebb_domain.com` (forumul principal)
  * Acasa
    * `http://your_nodebb_domain.com/admin/index` (vezi Acasa mai jos)
  * Setari
    * `http://your_nodebb_domain.com/admin/settings` (vezi Setari mai jos)

**Meniu lateral: NodeBB**
  * Acasa
    * `http://your_nodebb_domain.com/admin/index`
    * Toate linkurile trimit la pagina principala nodebb.com
      * Nota: Ar trebui toate linkurile sa trimita in acelasi loc?
    * Trebuie sa informam despre versiune si cum sa se verifice actualizarile (Vezi :doc:`Actualizare NodeBB <../upgrading/index>`)
      * Nota: ar ajuta un link catre cea mai recenta versiune?
    * Utilizatori Activi
      * listeaza numarul de utilizatori per cale-pagina (?)
      * Nota: nu este foarte clar ce inseamna calea sau cum sa vizitezi calea


  * Categorii
    * `http://your_nodebb_domain.com/admin/categories`
    * Filtre: Activ, Dezablat, Unit Tests
    * Lista de categorii:
      * Icoana, Nume, Desc, Actiune: Dezableaza
    * Actiuni: Salveaza, Adauga Noua

  * Utilizatori
    * `http://your_nodebb_domain.com/admin/users`
    * Filters: Latest utilizatori, Contributori Principali, Reputatia Maxima, Actiune: Cauta
    * Lista utilizatori:
      * Icoana, Link: Nume, Reputatie(stea), Numar posturi(creion), Actiune: Interzice acces
    * Actiune: Incarca mai mult

  * Groups
    * `http://your_nodebb_domain.com/admin/groups`
     * List of Groups
      * Name, Desc, Icon
    * Action: Delete Group
      * NOTE: What exactly can Groups be set up to do, besides Admin?

  * Topics
    * `http://your_nodebb_domain.com/admin/topics`
    * List of Topics
      * Name [link to topic], Posted When and By, Number posts (Topic+Replies), Thread Actions: Pin(pushpin), Lock(lock), Delete(trashcan)
    * Action: Load More Topics

    * Topic [from List of Topics link]
    * Normal View of Topic+Reply Posts but with:
      * Link, Edit, Delete Actions all enabled for each Post
      * Thread Tools:
        * Pin, Lock, Move, Delete

  * Themes (See :doc:`Theming NodeBB <../themes/create>`)
    * `http://your_nodebb_domain.com/admin/themes`
    * List of (Custom | Bootswatch) Themes
      * Actions: Use, Preview
    * Action: Revert (to base)

  * Plugins (See :doc:`Writing Plugins for NodeBB <../plugins/create>`)
    * `http://your_nodebb_domain.com/admin/plugins`
    * List of Plugins
      * Action: De/activate
    * Info on making plugins

  * Settings
    * `http://your_nodebb_domain.com/admin/settings`

    * General Settings
      * (textbox) Site Title
      * (textbox) Site Description
      * (textbox) Site Keywords
      * (textbox) Imgur Client ID
        * NOTE: How does this function?
      * (textbox) Maximum User Image Size

    * Privilege Thresholds (Use privilege thresholds to manage how much reputation a user must gain to receive moderator access.)
      * (textbox) Manage Thread
      * (textbox) Moderate utilizatori
      * (textbox) Create Pinned Topics

    * Email Settings
      * (textbox) Email Address (The following email address refers to the email that the recipient will see in the "From" and "Reply To" fields.)
      * (textbox) SMTP Server Host (Default: 127.0.0.1)
      * (textbox) SMTP Server Port

    * User Settings
      * (textbox) Minimum Username Length
      * (textbox) Maximum Username Length
      * (textbox) Minimum Password Length

    * Post Settings
      * (textbox) Post Delay
      * (textbox) Minimum Title Length
      * (textbox) Minimum Post Length
      * (checkbox) Use Outgoing Links Warning Page

    * Action: Save

  * Redis
    * `http://your_nodebb_domain.com/admin/redis`
    * Redis data storage stats

  * Logger
    * `http://your_nodebb_domain.com/admin/logger`
    * (checkbox) Enable HTTP logging
    * (checkbox) Enable socket.io event logging
    * (textbox) Path to log file

  * MOTD (Message of the Day)
    * `http://your_nodebb_domain.com/admin/motd`
    * (textarea) You can enter either full HTML or Markdown text.
    * (checkbox) Show the Message of the Day

**Side Menu: Social Authentication** (See :doc:`Enabling Social Network Logins <../admin/sso>`)

  * Twitter
  * `http://your_nodebb_domain.com/admin/twitter`

  * Facebook
  * `http://your_nodebb_domain.com/admin/facebook`

  * Google+
  * `http://your_nodebb_domain.com/admin/gplus`

**Side Menu: Plugins** (Shows installed plugins)

**Side Menu: Unit Tests** (Will run qunit tests)