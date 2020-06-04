//Rota: Endereço completo da requisição
//Recurso: Qual entidade estamos acessando do sistema

//GET   : Buscar uma ou mais informações do back-end
//POST  : Criar uma informação no back-end
//PUT   : Atualizar uma informação no back-end
//DELETE: Remover uma informação do back-end

//POST : http://localhost:3333/users    => Criar um usuário
//GET  : http://localhost:3333/users    => Listar um usuário
//GET  : http://localhost:3333/users/2  => Buscar dados do usuário com o id 2

//Request.params: Parâmetros que vem na própria rota que identificam um recurso
//Query.param   : Parâmetros que vem na própria rota geralmente opicionais para filtros, paginação
//Request.body  : Parâmetros para criação/atualização de informações

//knex('users').where('name', 'Alex').select('*')
//O knex será fundamental para uma possível mudança de banco de dados.