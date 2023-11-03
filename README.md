# Project-2

**Project Name:** "Setting up a Web Server on AWS EC2 with Terraform"

**Project Description:**

This project aims to create an AWS EC2 instance using Terraform and configure it to host a web server. The web server will be used to publish a simple "Hello, World!" web page.

**Project Objectives:**

1. Learn how to create an AWS EC2 instance using Terraform.

2. Learn how to install a web server (e.g., Apache or Nginx) on the created EC2 instance.

3. Prepare the EC2 instance for publication, ensuring the web page is accessible.

**Project Steps:**

1. **Preparing the Project Infrastructure:**

   - Create an AWS account or use an existing one.

2. **Setting Up the Terraform Environment:**

   - Install Terraform on your local machine.
   - Configure AWS credentials to interact with AWS services.

3. **Creating the Terraform Configuration File:**

   - Create a Terraform configuration file (e.g., `main.tf`).

4. **Creating the EC2 Resource:**

   - In the Terraform configuration file, define a resource that creates an EC2 instance. Configure the following properties:
     - Instance Type: For example, you can use "t2.micro."
     - Key Pair: Use an existing key pair in AWS or create a new one.
     - Security Groups: Choose the security groups to be used with the instance, or create a new security group.

5. **Web Server Installation:**

   - Gain SSH or RDP access to the EC2 instance.
   - Install the relevant web server software (e.g., Apache or Nginx).

6. **Creating a Web Page:**

   - Create a simple "Hello, World!" HTML page.

7. **Web Server Configuration:**

   - Configure the web server to serve the created web page as its root document.

8. **Publishing the Web Page to the EC2 Instance:**

   - Use Terraform to copy the web page to the EC2 instance.

9. **Enabling Internet Access:**

   - Configure the EC2 instance to be publicly accessible by setting up AWS Security Groups and Network ACLs.

10. **Testing Web Page Accessibility:**

    - Test access to the web page by using the EC2 instance's IP address or domain.

This project will help you learn the basics of creating an EC2 instance, setting up a web server, and publishing a web page using Terraform. It will also enhance your ability to manage infrastructure as code. This fundamental project can serve as a starting point for exploring more complex scenarios and further development.
Best of luck!

**Emre Sezer**
Z2H Cloud&Devops Admin


*****Türkisch version*****

**Proje Adı:** "Terraform ile AWS EC2 Üzerine Web Sunucusu Kurma"

**Proje Açıklaması:**

Bu proje, Terraform kullanarak AWS üzerinde bir EC2 örneği oluşturmayı ve bu örneğe bir web sunucusu kurmayı amaçlamaktadır. Web sunucusu, basit bir "Merhaba, Dünya!" web sayfasını yayınlamak için kullanılacaktır.

**Proje Amaçları:**

1. Terraform kullanarak AWS'de bir EC2 örneği oluşturmayı öğrenmek.

2. Oluşturulan EC2 örneği üzerine bir web sunucusu (örneğin, Apache veya Nginx) kurmayı öğrenmek.

3. EC2 örneğini yayınlanmaya hazır hale getirerek, web sayfasının erişilebilir olmasını sağlamak.

**Proje Adımları:**

1. **Proje Altyapısının Hazırlanması:**

   - AWS hesabı oluşturun veya mevcut bir AWS hesabını kullanın.

2. **Terraform Ortamının Hazırlanması:**

   - Terraform'ı bilgisayarınıza yükleyin.
   - AWS ile etkileşim kurmak için AWS kimlik bilgilerini yapılandırın.

3. **Terraform Konfigürasyon Dosyasının Oluşturulması:**

   - Bir Terraform konfigürasyon dosyası oluşturun (örneğin, `main.tf`).

4. **EC2 Kaynağının Oluşturulması:**

   - Terraform konfigürasyon dosyasında, EC2 örneği oluşturan bir kaynak tanımlayın. Özellikle şunları yapılandırın:
     - Örnek türü (Instance Type): Örneğin, "t2.micro" kullanabilirsiniz.
     - Özel anahtar (Key Pair): AWS'de tanımlı bir anahtar çifti kullanın veya yeni bir anahtar çifti oluşturun.
     - Güvenlik grupları (Security Groups): Örneği kullanacağınız güvenlik gruplarını seçin veya yeni bir güvenlik grubu oluşturun.

5. **Web Sunucusu Kurulumu:**

   - EC2 örneğine SSH veya RDP ile erişim sağlayın.
   - İlgili web sunucusunu (örneğin, Apache veya Nginx) kurun.

6. **Web Sayfası Oluşturma:**

   - Bir basit "Merhaba, Dünya!" HTML sayfası oluşturun.

7. **Web Sunucusu Yapılandırması:**

   - Web sunucusunun kök dizinini oluşturulan web sayfasının yerine işaret edecek şekilde yapılandırın.

8. **Web Sayfasını EC2 Örneğine Yayınlama:**

   - Terraform ile web sayfasını EC2 örneğine kopyalayın.

9. **İnternet Erişimini Sağlama:**

   - EC2 örneğinizin, dünyaya açık bir şekilde erişilebilmesini sağlamak için AWS Güvenlik Grupları ve IP tablolarını yapılandırın.

10. **Web Sayfasının Erişimini Test Etme:**

    - EC2 örneğinizin IP adresini veya alan adını kullanarak web sayfasına erişimi test edin.

Bu proje, temel bir EC2 örneği oluşturmanın yanı sıra bir web sunucusu kurmayı ve web sayfasını yayınlamayı öğrenmenize yardımcı olacaktır. Ayrıca, Terraform kullanarak altyapıyı kodla yönetme yeteneklerini geliştireceksiniz. Bu temel proje, daha karmaşık senaryoları incelemek ve geliştirmek için harika bir başlangıç olabilir.
BASARILAR!

**Emre Sezer**
**Z2H Coud&DevOps Admin**
