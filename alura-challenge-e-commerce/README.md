* 
        <h1>Cadastre-se</h1>
        <form class="register-form">
            <div class="full-box">
                <label for="email">E-mail</label>
                <input type="email" name="email" id="email" placeholder="Digite seu email" data-min-length="3">
            </div>
            <div class="half-box spacing">
                <label for="name">Nome</label>
                <input type="text" name="name" id="name" placeholder="Digite seu nome">
            </div>
            <div class="half-box">
                <label for="lastname">Sobrenome</label>
                <input type="text" name="lastname" id="lastname" placeholder="Digite seu sobrenome">
            </div>
            <div class="half-box spacing">
                <label for="password">Senha</label>
                <input type="password" name="password" id="password" placeholder="Digite uma senha">
            </div>
            <div class="half-box">
                <label for="passconfirmation">Sobrenome</label>
                <input type="password" name="passconfirmation" id="passconfirmation" placeholder="Confirme sua senha">
            </div>
            <div class="full-box">
                <input type="checkbox" name="agreement" id="agreement">
                <label for="agreement" id="agreement-label">Eu li e aceito os <a href="#">termos de uso</a></label>
            </div>
            <div class="full-box">
                <input type="submit" name="btn-submit" value="Registrar">
            </div>
        </form>
    

    script 
    /*class Validator {

    constructor() {
        this.validations = [
            'data-min-length',
        ]
    }

    //iniciar a validação dos campos
    validate(form) {

        let inputs = form.getElementsByTagName('input');

        let inputsArray = [...inputs];

        inputsArray.forEach(function(input) {
            
            for(let i = 0; this.validations.length > i; i++) {
                if(input.getAttribute(this.validations[i]) != null) {
                    console.log(input.getAttribute(this.validations[i]));
                    console.log('achou')
                }
            }

        }, this);

    }
}


let form = document.getElementById("register-form");
let submit = document.getElementById("btn-submit");

let validator = new Validator();

// evento que dispara as validações
submit.addEventListener('click', function(e) {

    e.preventDefault();

    validator.validate(form);

    console.log('funcionou');

});
*/