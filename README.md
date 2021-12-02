Ansible Role: Win-CSP-Cadesplugin
=========

Эта роль установит КриптоПро CSP 4.0 R4 (KC1) и КриптоПро ЭЦП Browser plug-in на ОС Windows.
КриптоПро CSP Ver=4.0.9963
КриптоПро ЭЦП Browser plug-in Ver=2.0.14071

Requirements
------------

None.

Role Variables
--------------

Доступные переменные перечислены вместе со значениями по умолчанию (см. `defaults/main.yml`). Роль добавит список доверенных узлов для КриптоПро ЭЦП Browser plug-in:|http://zakupki.gov.ru|https://bus.gov.ru|https://cert.roskazna.ru|https://fzs.roskazna.ru|https://ssl.budgetplan.minfin.ru|https://www.cryptopro.ru|https://*.sufd.budget.gov.ru|https://lk-fzs.roskazna.ru|https://vrs.cert.roskazna.ru|http://*.budget.gov.ru|https://*.budget.gov.ru

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - win_csp_cadesplugin

License
-------

BSD

Author Information
------------------

Chubik Sergey, sergey.chubik@mail.ru.
Chubik Sergey, chubik@ekaterinburg.fsin.uis.
