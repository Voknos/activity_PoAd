
# **Markdown**

## 1. **Pattern Name and Classification:**
* Padrão Template Method
* Padrão Comportamental

## 2. **Intent:**
* Permite que as subclasses façam modificações deste algoritimo sem alterar a estrutura

## 3. **Motivition:**
* Alterações no algoritmo pode ser feitas de forma genérica ou específica em cada componente específico

## 4. **Applicability:**
* Aplicação que possui estrutura hierárquica e um algoritmo que pode ser dividido em etapas.
* Dois ou mais componentes diferentes implementam esse algoritmo, possuindo várias
  semelhanças mas alguns diferenças na implementação de algumas etapas do algoritmo.
* Alterações no algoritmo pode ser feitas de forma genérica ou específica e mcada componente específico
* Útil em cenários em que se tem gerador automático de código.

## 5. **Structure:**
![TemplateMethod](https://github.com/Voknos/Activity_PoAd/blob/master/Template%20Method/TemplateMethod.png)

## 6. **Participants:**

######    **FrameworkClass:**
* Define o templateMethod que é responsável por chamar os demais métodos.
* Especifica os métodos abstratos das etapas de execução

######    **ApplicationClassOne/ApplicationClassTwo:**
* Redefine, quando necessário, algumas etapas do algoritmo especificado em FrameworkClass

## 7. **Sample Code:**
* Exemplo do TemplateMethod de uma calculadora que realizar a Soma e a Subtração de valores

[github.com/Voknos/Activity_PoAd/tree/master/Template%20Method/templateMethodUlt](https://github.com/Voknos/Activity_PoAd/tree/master/Template%20Method/templateMethodUlt)



