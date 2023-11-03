class heroi {
    constructor(tipo, ataque){
        this.tipo = tipo;
        this.ataque = ataque;
    }
    escrever(){
        console.log(`o ${this.tipo} atacou usando ${this.ataque}`);
    }
}

const magao = new heroi("mago" , "magia");
const guerreirao = new heroi("guerreiro" , "espada");
const mongem = new heroi("monge" , "artes marciais");
const ninjao = new heroi("ninja" , "shuriken");
magao.escrever()
guerreirao.escrever()
mongem.escrever()
ninjao.escrever()
