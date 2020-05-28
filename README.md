# Jumpseller - Multibanco 

Para configurar o Multibanco na sua loja Jumpseller deve, em primeiro lugar, contactar o HiPay e
solicitar uma conta de produção ou de teste, indicando que pretende utilizar na plataforma
Jumpseller.

Serão fornecidas as credenciais e uma chave privada do método de pagamento.

Poderá então proceder à configuração da conta, acedendo ao Painel de Gestão da loja e seguindo
os seguintes passos:

1. Escolher no menu, Definições e de seguida Pagamentos.
2. Na caixa de escolha, selecionar “Pagamento Externo” e clicar em “Adicionar método”
3. Preencher o formulário com o nome que pretende para o método de pagamento, por exemplo, Multibanco. No url do método de pagamento deve colocar https://jumpseller-multibanco.hipay.pt/. Na chave do método o username das credenciais fornecidas. Na chave privada o valor fornecido juntamente com as credenciais, para o efeito.

Gravar e verificar que o novo método se encontra disponível na lista de métodos de pagamento.

## Como verificar a referência Multibanco disponibilizada ao cliente?

Aceder ao detalhe do Pedido e na listagem do Histórico de mensagens escolher “Mostrar Registros” em “Pagamento não foi confirmado por Pagamento Externo”. Verificar o campo “x_message”, que contém a entidade e referência fornecida ao cliente durante o checkout.

Para mais detalhes ver o manual em PDF.
