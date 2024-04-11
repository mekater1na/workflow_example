Привет! 

В данном репозитории расположен пример workflow, который по умолчанию уже добавлен во все репозитории курса Base Level Course.

Если в вашем репозитории нет файла **.github/workflows/test.yml**, вам необходимо добавить его самостоятельно, если хотите 
иметь возможность самостоятельно анализировать причины несдачи практического задания.

Для того, чтобы в своем репозитории иметь возможность просмотра логов прогона, вам необходимо:
1. создать в корне своего репозитория директорию с файлом **.github/workflows/test.yml**;
2. скопировать данные из файла [example.yml](example.yml) в свой файл **test.yml**;
3. в [строке 10](https://github.com/mekater1na/workflow_example/blob/42a1b23e85f494c6978c0b55f482bc57a305e830/example.yml#L10) вместо <номер задания>
указать номер вашего задания. Если у вас задания с 3 по 9, то необходимо прописать 03 - 09 соотвественно. Для заданий с 10 по 15 так делать не нужно. 

Пример:
Вы далаете практическое задание номер 6. Для того, чтобы иметь возможность просматривать логи вашего прогона, необходимо в 10ой строке файла **test.yml** прописать
github.com/QA-Fullstack-SDET/blc_06_test.

Вы далаете практическое задание номер 11. Для того, чтобы иметь возможность просматривать логи вашего прогона, необходимо в 10ой строке файла **test.yml** прописать
github.com/QA-Fullstack-SDET/blc_11_test.
