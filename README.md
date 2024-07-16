public void print_tree() {
        String space = "  ";
        String repeated = space.repeat(this.Level);
        System.out.println((repeated + this.name));
        for (Node child : this.children) {
            child.print_tree();
        }
