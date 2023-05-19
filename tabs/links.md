---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Links"
    info: "Your Links page description."

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Organizations"
      type: id_orgs
      color: "gray"
    - title: "Personal"
      type: id_personal
      color: "#F4A273"
    - title: "Programming"
      type: id_programming
      color: "#62b462"

  list:
    -

    # jekyiiliquid
    - type: id_orgs
      title: "UCI Rocket Project - Liquids"
      url: "https://www.rocket.eng.uci.edu/team-formation-2021-2022/"
      info: "We launched a bi-propellant liquid fuel rocket that went up to 9300ft. Our aim is to push the boundaries of collegiate rocketry"
    - type: id_orgs
      title: "IEEE @UCI"
      url: "https://www.instagram.com/ieee_uci/"
      info: "I was part of the Micrmouse Project which designed and built a roboot capable of autonomously solving a maze at high speeds."
    - type: id_orgs
      title: "Henry Samueli School of Engineering"
      url: "https://engineering.uci.edu/"
      info: "I am a student in the EECS department currently pursuing a degree in Computer Science and Engineering."

    - type: id_personal
      title: "Resume"
      url: "/assets/resume.pdf"
      info: "This is my resume."
    - type: id_personal
      title: "Portfolio Website"
      url: "https://shipp02.github.io"
      info: "You are here right now. Don't get stuck in a recursive loop."

---
