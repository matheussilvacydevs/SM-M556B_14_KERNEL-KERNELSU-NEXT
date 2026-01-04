# SM-M556B_14_KERNEL

Este repositório contém o **kernel stock** do Samsung Galaxy M55 (SM-M556B) com Android 14 e One UI 6.1.

⚠️ **Atenção:** Este kernel é fornecido apenas para **download e referência**. Ele serve como base para a criação de **kernels customizados** e não inclui nenhuma modificação própria.

## Conteúdo do repositório
- Arquivos completos do kernel stock (Android 14 / One UI 6.1)
- Estrutura de pastas oficial do kernel Samsung
- Configurações padrão do dispositivo

## Objetivo
Este repositório foi criado para desenvolvedores que desejam:
- Estudar a estrutura do kernel stock do SM-M556B
- Criar kernels customizados a partir da base oficial
- Compilar versões modificadas para fins de aprendizado ou desenvolvimento próprio

## Instruções de uso
1. Clone o repositório:
```bash
git clone https://github.com/SEU_USUARIO/SM-M556B_14_KERNEL.git
cd SM-M556B_14_KERNEL
```

2. Use como base para compilar ou modificar seu kernel customizado:
```bash
# Ajuste conforme seu toolchain
export CROSS_COMPILE=aarch64-linux-gnu-
export ARCH=arm64
make O=out msm_m55_defconfig
make -j$(nproc)
```

> 🔹 Este repositório **não fornece kernels compilados prontos para flash**, apenas os fontes do kernel stock.

## Licença
Este projeto mantém a **licença original do kernel Samsung**, normalmente GPL v2.  
Para detalhes, veja o arquivo  incluído no repositório.

