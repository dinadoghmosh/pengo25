<template>
    <aside id="left-panel" class="left-panel">
        <nav class="navbar navbar-expand-sm navbar-default">

            <div class="navbar-header">
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#main-menu" aria-controls="main-menu" aria-expanded="false" aria-label="Toggle navigation">
                    <i class="fa fa-bars"></i>
                </button>
                <a class="navbar-brand" href="./">Pengo</a>
                <a class="navbar-brand hidden" href="./">p</a>
            </div>

            <div id="main-menu" class="main-menu collapse navbar-collapse">
                <ul class="nav navbar-nav">
                    <li class-active="active" to="/" exact >
                        <router-link to="/" > 
                            <i class="menu-icon fa fa-home"></i>Home 
                        </router-link>
                    </li>
                    <h3 class="menu-title">Employees</h3><!-- /.menu-title -->
                    <li class="menu-item-has-children dropdown">
                        <a href="#" class="dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"> <i class="menu-icon fa fa-laptop"></i>Employees</a>
                        <ul class="sub-menu children dropdown-menu">
                            <li><i class="fa fa-plus-square"></i><router-link to="/addEmployee" >Add Employye</router-link
                            ></li>
                        <li><i class="fa fa-address-card"></i><router-link to="/Employeeoperation" >Employee oper</router-link
                            ></li>

                                               </ul>
                    </li>
                    

                    <h3 class="menu-title">Student</h3><!-- /.menu-title -->

                    <li class="menu-item-has-children dropdown">
                        <a href="#" class="dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"> <i class="menu-icon fa fa-tasks"></i>Student</a>
                        <ul class="sub-menu children dropdown-menu">
                            <li><i class="fa fa-plus-square"></i><router-link to="/addstudent">Add Student</router-link></li>
                            <li><i class="fa fa-address-card"></i><router-link to="/studentopera">Student opera</router-link></li>
                        </ul>
                    </li>
                  
                   
                </ul>
            </div><!-- /.navbar-collapse -->
        </nav>
    </aside>
</template>
