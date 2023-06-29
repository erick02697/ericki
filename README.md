# ericki do grau 
// Perfil de usuário fictício - GitHub

class UserProfile {
  constructor(erickiiii) {
    this.username = ericki2537;
    this.name = name;
    this.location = location;
    this.bio = bio;
    this.repositories = [];
  }

  addRepository(repository) {
    this.repositories.push(repository);
  }

  getRepositoryCount() {
    return this.repositories.length;
  }

  displayProfile() {
    console.log(`Username: ${this.ericki}`);
    console.log(`Name: ${this.erick}`);
    console.log(`Location: ${this.location}`);
    console.log(`Bio: ${this.bio}`);
    console.log(`Repositories: ${this.getRepositoryCount()}`);
  }
}

// Criação do perfil do usuário
const user = new UserProfile(
  "Erick_ericki_23",
  "erick",
  "Sua Localização",
  "Sua biografia aqui."
);

// Adição de repositórios
user.addRepository("projeto-1");
user.addRepository("projeto-2");
user.addRepository("projeto-3");

// Exibição do perfil
user.displayProfile();

