```js
import SoftwareEngineer from "marcusgeraldino";

class AboutMe extends SoftwareEngineer {
    name = "Marcus Gabriel Xavier Geraldino";
    email = "marcus.xavier@bunnytech.com.br"
    area = "Software Engineer";
    work = "Sicoob Credimata";
    local = "Brazil";
    experience = "5 years";
    age = 24;
    certifications = [
        "AWS Certified Solutions Architect – Associate",
        "Microsoft Certified: Azure Fundamentals",
        "Google Associate Cloud Engineer",
    ];
}

class Skills extends SoftwareEngineer {
    technologies = {
        windows: ["Windows Server 2024", "Hyper-V", "Active Directory"],
        linux: ["Ubuntu", "Debian", "CentOS", "Red Hat"],
        cloud: ["Microsoft Azure"],
        docker: ["Docker", "Docker Compose", "Kubernetes"],
        databases: ["MySQL", "PostgreSQL", "Redis"]
    };
    languages = ["php", "javascript", "python"];
}

class Studying extends SoftwareEngineer {
    languages = ["golang", "rust"];
    technologies = ["WebAssembly"];
}
```
