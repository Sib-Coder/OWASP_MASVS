# MASVS-CODE-4

## Control

Приложение проверяет и обрабатывает все ненадежные входные данные.

## Description

Приложения имеют множество точек ввода данных, включая пользовательский интерфейс, IPC, сеть, файловую систему и т.д. Эти входящие данные могли быть непреднамеренно изменены ненадежными участниками и могут привести к обходу критических проверок безопасности, а также к классическим инъекционным атакам, таким как SQL-инъекция, XSS или небезопасная десериализация. Этот элемент управления гарантирует, что эти данные рассматриваются как ненадежные входные данные и должным образом проверяются и обрабатываются перед использованием.
