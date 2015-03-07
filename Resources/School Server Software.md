# School Server Software

The school should be running some services locally. This garentees that senstive documents and other information are in the hands of the school, and not a third party. Also, running your own website is more cost effective for large schools then having it outsourced.

## Ubuntu Server (C1, I3, U3)

Ubuntu Server is a powerful tool for managing the school website, or other web driven technologies. Wordpress and other tools are relatively easy to set up.

* [Homepage](http://www.ubuntu.com/server)

## Ubuntu Cloud (C2, I4, U2)

Ubuntu Cloud is a new approach to managing hardware and software. Landscape is a paid tool that makes light work of managing multiple school machines.

* [Homepage](http://www.ubuntu.com/cloud)

## Ubuntu's Juju (C1, I2, U2)

Juju is software designed to easily deploy other software. It is available for Windows, Mac, and Ubuntu, and provides a near one click install method for complex server software (like wordpress, Drupal, Xwiki) It can be configured either through a GUI or the commandline. Unlike Bitnami, software created using Juju can be told to use the same database. It is more useful for setting up applications that need to communicate with each other. It integrates well with other ubuntu projects, and is a natural choice for a school pursuing Ubuntu as their only operating system.

* [Homepage](https://jujucharms.com/)
* [Documentation](https://jujucharms.com/docs/)

## Bitnami (C2, I2, U2)

Bitnami is a website that strives to create one click installs for complex serve packages. It is by far the easiest way to install and manage server software. It has a large collection existing software, and an active community.

* [Homepage](https://bitnami.com/)

## Wordpress (C1, I1, U1)

Wordpress it the most common and easiest content mangement system. It was originally designed as a blogging platform, but through the years it has evolved into a much broader application. In terms of changing content on a website, Wordpress is very easy to work with. In addition to providing a free blog, one can also download wordpress and host the application yourself. I reccommend schools to create their public website using this platform (and installed through Bitnami). There are both free and paid themes, but it is not difficult to write your own if you've done some programming. From here I would link to other online services, but the Wordpress installation provides a great front page to your school.

* [Homepage](https://wordpress.org/)
* [Bitnami Install](https://bitnami.com/stack/wordpress)

## Open Atrium (C1, I2, U3)

Open Atrium is a collection of tools built on top of a Drupal CMS dedicated to team collaboration. It does teams and organizational spaces much better then Wordpress. Open Atrium is much better at having multiple colloborate in a workplace setting. I could see this as a valuable tool for in house school management. As it is based off Drupal, you get that powerful customization that marks that CMS. Unfortunately, it is less user friendly, which could be a strong deterant for some.

* [Homepage](http://openatrium.com/#!/)
* [Bitnami Install](https://bitnami.com/stack/openatrium)

## XWiki (C1, I2, U2)

Xwiki is much like Open Atrium for creating spaces for content. It does not have the same level of workplace support as OA, but it is easier to use in my opinion. True to being a wiki, pages that are created can be revised and edited. It is the best in my opinion for a collaborate wiki for schools. Currently there is not a bitnami installer, but should be soon. (as of writing Feb 2015)

* [Homepage](http://www.xwiki.org/xwiki/bin/view/Main/)
* [Bitnami Install](https://bitnami.com/stack/xwiki)

## Docuwiki (C1, I2, U3)

Dokuwiki is a wiki aimed at providing information. It does not have the level of collaboration present in XWiki and Open Atrium, but it does present information in a much cleaner interface. It is ideal for housing a living document that will be edited by multiple people. Schools constitution, and perhaps curriculum guides would be best suited to this form of delivery. Unlike other CMS's, it does not have a WYSIWYG editing interface, which makes it harder to learn how to properly edit documents.

* [Homepage](https://www.dokuwiki.org/dokuwiki#)
* [Bitnami Install](https://bitnami.com/stack/dokuwiki)

