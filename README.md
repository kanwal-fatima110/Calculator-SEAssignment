# Calculator-SEAssignment
Project assignment given by Dr. Gulsher Laghari

<project name="Calculator" default="run">
    <!-- Project properties -->

    <target name="clean">
        <!-- Clean target implementation -->
    </target>

    <target name="compile" depends="clean">
        <!-- Compile target implementation -->
    </target>

    <target name="create-jar" depends="compile">
        <!-- Create JAR target implementation -->
    </target>

    <target name="run" depends="create-jar">
        <!-- Run target implementation -->
    </target>

    <target name="test" depends="compile">
        <!-- Test target implementation -->
    </target>

</project>
