Bloco 1: Privacidade e Preparação de DadosRemoção de Colunas (df.drop): Apaga colunas com dados sensíveis (nomes, CPF, contas) e informações inúteis. Protege a privacidade (LGPD) e evita que a IA crie regras falsas ou perca desempenho devido a ruído.   

Normalização Min-Max: Transforma todos os números para a mesma escala (entre $0.0$ e $1.0$). Evita que variáveis com valores grandes (como salário) dominem a IA e façam variáveis com valores pequenos (como idade) serem ignoradas.

Guardrails no Prompt: Regras rígidas de segurança inseridas no prompt do sistema para impedir que a IA exponha dados pessoais, crie conteúdos difamatórios ou viole a privacidade de utilizadores.

Bloco 2: Como a IA Aprende e FalhaEntradas ($X$) e Saídas ($y$): As variáveis de entrada $X$ foram os dados digitais públicos do Ash (posts, mensagens, áudios) e a saída $y$ foi a geração do comportamento do clone.   

Overfitting (Superajuste): Ocorre quando o modelo decora os dados de treino mas falha no mundo real. O clone aprendeu a imagem pública do Ash na internet ($X$), mas não os comportamentos reais e não observados do dia a dia, falhando na convivência.   

Overfitting (Superajuste): Ocorre quando o modelo decora os dados de treino mas falha no mundo real. O clone aprendeu a imagem pública do Ash na internet ($X$), mas não os comportamentos reais e não observados do dia a dia, falhando na convivência.   

Bloco 3: Memória e Análise de Dados
Grain vs. Git/GitHub: O implante de memórias funciona como o Git: cada recordação é um commit (uma fotografia gravada no tempo) e a revisão de memórias é a consulta ao histórico de alterações.

Governança de Dados: Ter histórico é fundamental na engenharia de software para rastrear e corrigir erros, mas exige regras estritas de eliminação e privacidade para não gerar comportamentos obsessivos.

Viés de Confirmação e Gráficos: O protagonista focou-se em imagens isoladas (ruído/outliers) para confirmar as suas suspeitas. O uso de gráficos de dispersão (Scatter Plot) e Pairplot ajuda o cientista a analisar a tendência real da base completa e evitar conclusões erradas.

Bloco 4: Métricas e Tomada de DecisãoConsequência das Métricas: Um coeficiente $R^2$ baixo indica pouca confiabilidade no modelo, enquanto um erro RMSE alto significa previsões muito distantes da realidade.  


Erros de Previsão na Crise:

Falso Positivo (dizer que uma chamada real é golpe): A polícia manda ignorar e a vítima real fica desprotegida.

Falso Negativo (dizer que um golpe de IA é um sequestro real): A família entra em pânico e transfere dinheiro para criminosos.


Estrutura do Pitch de Crise: Deve conter 5 partes sequenciais: Abertura (captar atenção), Problema (extorsão por clonagem de voz), Dados (base limpa e normalizada), Solução (modelo preditivo biométrico) e Impacto/Próximos Passos (ações imediatas com base no $R^2$ de $0.94$). 
