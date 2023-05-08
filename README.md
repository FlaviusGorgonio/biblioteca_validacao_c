# biblioteca_validacao_c
Biblioteca de funções de validação na linguagem C

Rotinas de Validação

Descreva as principais funções de validação necessárias ao seu projeto

Validação de CPF (Todos)
Aceitar somente dígitos, sem pontos ou traços
Verificar se o CPF é válido (regras de validação)
Recebe o CPF no formato texto e devolve 0 ou 1
Assinatura da função
int valida_cpf(char *);

Validação de CNPJ
Aceitar somente dígitos, sem pontos ou traços
Verificar se o CNPJ é válido (regras de validação)
Recebe o CNPJ no formato texto e devolve 0 ou 1
Assinatura da função
int valida_cnpj(char *);

Validação de data  (Todos)
Aceitar somente dígitos e barra (/)
Verificar se a data é válida (se existe no calendário)
Verificar se o ano é bissexto
Recebe a data no formato texto e devolve 0 ou 1
Assinatura da função
int valida_data(char *);



Validação de nome (Todos)
Aceitar somente letras e acentuação
Verificar se o nome é válido (regras de validação) 
int valida_nome(char *); 

Validação de Email (Todos)
      a. Aceitar somente letras, dígitos, underline, ponto e arroba
      b. Verificar se o email é válido (se segue o padrão pré e pós arroba)
	int valida_email(char *);

Validação de celular (Todos)
Aceitar somente números
Verificar se o celular é válido (regras de validação: ddd e prefixo 9)
int valida_celular(char *);

      7.  	Validação de ID ou Código (Todos)
Aceitar apenas dígitos
Verificar ID/código (se já existe)
int valida_id(char *);

      8. Validação de hora (Pedro)
Aceitar números e carácter especial(:)
Verificar se a hora é válida
int valida_hora(char *);         
