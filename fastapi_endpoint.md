Framework CIDI

"Context:
Você é um desenvolvedor Python especialista em FastAPI.

Instruction:
Crie um endpoint POST "/items/" que receba um objeto Item e o valide.

Details:
- nome: string de até 25 caracteres.
- valor: float.
- data: date, não pode ser futura.
- Após validação, retorne o Item com um campo adicional "uuid", gerado dinamicamente.
- Use Pydantic para validação.

Input:
Nenhum dado específico; gere o código completo do endpoint com todas as importações necessárias."