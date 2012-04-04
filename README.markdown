Provides the possibility to extend DiscriminatorMap on Inheritance Mapped classes with Class Table Inheritance.

Example configuration (config.yml):

        netpositive_discriminator_map:
            discriminator_map:
                content:
                    entity: Netpositive\CmsBundle\Entity\Content
                    children:
                        course: University\CmsBundle\Entity\Content\Course
                        phonebook_entry: University\CmsBundle\Entity\Content\PhonebookEntry


parent class:

* Netpositive\CmsBundle\Entity\Content

parent table name:

* content

children classes:

* University\CmsBundle\Entity\Content\Course
* University\CmsBundle\Entity\Content\PhonebookEntry

children table names:

* course
* phonebook_entry