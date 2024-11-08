# Nome do compilador
CXX = g++

# Flags de compilação
CXXFLAGS = -std=c++11 -Wall

# Nome do arquivo executável
TARGET = hello

# Arquivos fonte
SRC = hello.cpp

# Regra para compilar o programa
$(TARGET): $(SRC)
	$(CXX) $(CXXFLAGS) $(SRC) -o $(TARGET)

# Regra para limpar os arquivos compilados
clean:
	rm -f $(TARGET)
