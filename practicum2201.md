# Как выйти их Vim редактора при выполнении команды git commit?   
> +++

    :q! - выйти без сохранения
# Как создать новую ветку и сразу на нее перейти? 
> знала, на семинарах научили.

    git checkout -b new_branch
# Как переименовать ветку? 
> +++

    Находясь в ветке, которую нужно переименовать набрать команду git branch -m new_name
# Как создать конфликт и удачно его разрешить? 
> + на сериминарах хорошо объяснили.

    Слить новую ветку в мейн, и потом на эти же строки пытаться слить еще одну ветку. В конфикте выбрать вариант решения и сохранитьь, add, commit.
# Как создать новый удаленный репозиторий?
> + на сериминарах хорошо объяснили.

    в ЛК хаба тыкнуть создать репо (странный вопрос)
# Как связать удаленный репозиторий с локальным?
> + на сериминарах хорошо объяснили.

    пройтись по командам подсказки на хабе (3 варианта)
# Как сделать пулл реквест?
>  + на сериминарах хорошо объяснили.
    git push, из репо в ЛК хаба кнопка предложить изменения (pull request)