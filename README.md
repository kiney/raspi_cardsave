# raspi_cardsave
Ansible role for raspian to go easy on the system sd card

My Raspberry Pi ate sd cards like candy, this ansible role aims to solve that
problem.

It works by mounting some stuff als tmpfs and/or deactivating swap.
Defaults are chosen to be sane for most cases but can be customized in host- or
group vars.
