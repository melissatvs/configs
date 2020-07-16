[Ir para Principal](../readme.md)

# C#

---

## Conversões

### Enum para String

`EnumCustom.NomeDoItemEnum.ToString();`

### Enum para Int

`(int)EnumCustom.NomeDoItemEnum;`

### String para Enum

`(EnumCustom)Enum.Parse(typeof(EnumCustom), stringX);`

---

## Manipulando objetos

### Lista

#### Adicionar novo item no fim da lista

`Lista.Add(item);`

#### Adicionar novo item no início da lista

`Lista.Insert(0, item);`

---

### Array

### Vetor de int para string

`string result = string.Join("", array);`