# Получаем и выводим весь список контактов в виде таблицы (console.table)
node index.js --action list
https://monosnap.com/file/9DDu4suCgLcEPlnoLARXJEq0KENqo4

# Получаем контакт по id
node index.js --action get --id 5
https://monosnap.com/file/GdcSyAi9pOC1a8JdPbX6VB1jqbMC6B

# Добавялем контакт
node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/nEtYMOgFJ27qCkaSdyF2PqwHcvVkn9

# Удаляем контакт
node index.js --action remove --id=3
https://monosnap.com/file/zQjYRclRiXzipoII6bsDGM1CpJOjr6
