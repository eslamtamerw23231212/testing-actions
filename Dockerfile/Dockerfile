
FROM openjdk:17

WORKDIR /app

# Copy the Java source file into the container
COPY print.py /app/print.py

# Compile the Java program
RUN python print.py

# Set the command to run the compiled Java program
CMD ["python", "print.py"]
