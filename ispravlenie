import os

q = 'В какой стране построено самое высокое здание в мире?'
p = [
    {
        'value': 'оаэ',
        'correct': True,
        'visible': True
    },

    {
        'value': 'франция',
        'correct': False,
        'visible': True
    },

    {
        'value': 'сша',
        'correct': False,
        'visible': True
    },

]

def printOptions(options):
    print('Варианты ответов:')


    for option in options:
        if not option['visible']:
            continue
        print('○ {}'.format(option['value']))


def getAnswer(question, options):
    finished = False

    while not finished:
        print('Вопрос: {}'.format(question))
        printOptions(p)
        os.system('clear')

        answer = input().lower()

        for option in p:
            if option['value'] == answer:
                if option['correct']:
                    finished = True
                    print('Молодец! Все ты знаешь.')
                else:
                    option['visible'] = False
                    print('Ошибка! Пробуй еще раз!')

                break
getAnswer(q, p)

l = 'Кто написал первую машинную программу?'
n = [
{
        'znach': 'ада лавлейс',
        'correct': True,
        'visible': True
    },

    {
        'znach': 'леонардо да винчи',
        'correct': False,
        'visible': True
    },

    {
        'znach': 'братья люмьер',
        'correct': False,
        'visible': True
    },
]

def printVariants(variants):
    print('Варианты ответов:')

    for variant in variants:
        if not variant['visible']:
            continue
        print('○ {}'.format(variant['znach']))


def getAnswers(question, variants):
    finished = False

    while not finished:
        print('Вопрос: {}'.format(question))
        printVariants(n)
        os.system('clear')

        answer = input().lower()

        for variant in n:
            if variant['znach'] == answer:
                if variant['correct']:
                    finished = True
                    print('Круто! Мне нравится твой настрой')
                else:
                    variant['visible'] = False
                    print('Чего-то ты не в ресурсе. Попробуй еще разок!')

                break
getAnswers(l, n)


b = 'Сколько лет правила королева Елизавета I (английская)?'
d = [
{
        'otv': '45',
        'correct': True,
        'visible': True
    },

    {
        'otv': '60',
        'correct': False,
        'visible': True
    },

    {
        'otv': '70',
        'correct': False,
        'visible': True
    },
]

def printVariantiki(variantiks):
    print('Варианты ответов:')

    for variantik in variantiks:
        if not variantik['visible']:
            continue
        print('○ {}'.format(variantik['otv']))


def getOtvetikis(question, variantiks):
    finished = False

    while not finished:
        print('Вопрос: {}'.format(question))
        printVariantiki(d)
        os.system('clear')

        answer = input().lower()

        for qws in d:
            if qws ['otv'] == answer:
                if qws ['correct']:
                    finished = True
                    print('Круто! Мне нравится твой настрой. Мы продолжаем!')
                else:
                    qws['visible'] = False
                    print('Чего-то ты не в ресурсе. Попробуй еще разок!')

                break
getOtvetikis(b, d)


x = 'В каком году последний штат США ратифицировал поправку о равных правах?'
y = [
    {
        'ch': '2019',
        'correct': True,
        'visible': True
    },

    {
        'ch': '1975',
        'correct': False,
        'visible': True
    },

    {
        'ch': '1890',
        'correct': False,
        'visible': True
    },

]


def printChtos(chtos):
    print('Варианты ответов:')

    for chto in chtos:
        if not chto['visible']:
            continue
        print('○ {}'.format(chto['ch']))


def getChtos(question, chtos):
    finished = False

    while not finished:
        print('Вопрос: {}'.format(question))
        printChtos(y)
        os.system('clear')

        answer = input().lower()

        for option in y:
            if option['ch'] == answer:
                if option['correct']:
                    finished = True
                    print('Великолепно! Остался финальный вопрос. Готовься!')
                else:
                    option['visible'] = False
                    print('А если подумать?')

                break
getChtos(x, y)

r = 'Кто на самом деле открыл структура ДНК?'
e = [
    {
        'fin': 'розалинд франклин',
        'correct': True,
        'visible': True
    },

    {
        'fin': 'мария складовская-кюри',
        'correct': False,
        'visible': True
    },

    {
        'fin': 'хеди ламарр',
        'correct': False,
        'visible': True
    },

]


def printFinals(finals):
    print('Варианты ответов:')

    for fins in finals:
        if not fins['visible']:
            continue
        print('○ {}'.format(fins['fin']))


def getFinals(question, finals):
    finished = False

    while not finished:
        print('Вопрос: {}'.format(question))
        printFinals(e)
        os.system('clear')

        answer = input().lower()

        for option in e:
            if option['fin'] == answer:
                if option['correct']:
                    finished = True
                    print('Ну все! Теперь ты рафинированный интеллектуал. Живи с этим.')
                else:
                    option['visible'] = False
                    print('Ну, одна ошибка - не трагедия. Еще потыкай.')

                break
getFinals(r, e)

